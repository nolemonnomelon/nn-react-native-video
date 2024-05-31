

## 6.1.2 (2024-05-31)


### Bug Fixes

* 🐛 support ios cameraroll ([285e9ca](https://github.com/nolemonnomelon/nn-react-native-video/commit/285e9ca8817ff7de4f6ac2d4cf51f944ef5237c9))
* access on undefined variable ([dc75d23](https://github.com/nolemonnomelon/nn-react-native-video/commit/dc75d236c56dd7a09848f6b4b8803cf1c3113694))
* add allowsExternalPlayback missing on ReactVideoProps ([#3398](https://github.com/nolemonnomelon/nn-react-native-video/issues/3398)) ([72679a7](https://github.com/nolemonnomelon/nn-react-native-video/commit/72679a7d639b9c000e060af0dbab7c862c180b00))
* add missing `audioOutput` prop ([#3450](https://github.com/nolemonnomelon/nn-react-native-video/issues/3450)) ([f20d68b](https://github.com/nolemonnomelon/nn-react-native-video/commit/f20d68b814c062f5f0df576b71bc9a9fc7ea67d9))
* add missing node_modules paths to metro.config.js of basic example app ([#3555](https://github.com/nolemonnomelon/nn-react-native-video/issues/3555)) ([d505de5](https://github.com/nolemonnomelon/nn-react-native-video/commit/d505de5910a22ab9a0d7429e6b88a81cd2594b9c))
* add missing shutterColor type ([#3561](https://github.com/nolemonnomelon/nn-react-native-video/issues/3561)) ([ba00881](https://github.com/nolemonnomelon/nn-react-native-video/commit/ba00881ddcd53c2f5a4e1fc6e30cb5eb7ef674a3))
* add relayout when fullscreenview dismiss ([5b2a474](https://github.com/nolemonnomelon/nn-react-native-video/commit/5b2a4741dd124009c9a3c136943698b966539b8d))
* add stub for IMA and option to enable it on demand ([57b4a76](https://github.com/nolemonnomelon/nn-react-native-video/commit/57b4a767759e665ed2e24c3fbbdf073da9c83b65))
* add the missing dependency ([40e8d94](https://github.com/nolemonnomelon/nn-react-native-video/commit/40e8d9474fc20cc2aedd54ebac07c81b92b76f45))
* **android, exoplayer:** ensure playback progress is reported even if paused ([8782755](https://github.com/nolemonnomelon/nn-react-native-video/commit/8782755cd6bbb99dbbfb2751fddf2125fdad84b1))
* **android:** add explicitly dependancy to androidx.activity ([#3410](https://github.com/nolemonnomelon/nn-react-native-video/issues/3410)) ([908e30f](https://github.com/nolemonnomelon/nn-react-native-video/commit/908e30f9b8d950fa1423a10d4b08135b6cc4d43a))
* **android:** add support of square video format ([3675dc2](https://github.com/nolemonnomelon/nn-react-native-video/commit/3675dc27899d1338c4881930c58e3cc9ff59f41e))
* **android:** ads build and enable ads in android sample ([#3376](https://github.com/nolemonnomelon/nn-react-native-video/issues/3376)) ([fe89122](https://github.com/nolemonnomelon/nn-react-native-video/commit/fe89122524826093689118a4515802d83ca88679))
* **android:** allow multidex support ([02b1399](https://github.com/nolemonnomelon/nn-react-native-video/commit/02b1399463c7f6869aec4648f4d094aeb0f71192))
* **android:** avoid blinking on video track change ([#3782](https://github.com/nolemonnomelon/nn-react-native-video/issues/3782)) ([7b1e129](https://github.com/nolemonnomelon/nn-react-native-video/commit/7b1e1293f67c0e25e0763d08d830fcf192bb713c))
* **android:** catch errors in `performOnPlayerView` ([#3685](https://github.com/nolemonnomelon/nn-react-native-video/issues/3685)) ([3e35326](https://github.com/nolemonnomelon/nn-react-native-video/commit/3e3532691ad42a53b9136fd52eb7f9a578e21b91))
* **android:** check disableFocus when state is ready ([#3494](https://github.com/nolemonnomelon/nn-react-native-video/issues/3494)) ([366c841](https://github.com/nolemonnomelon/nn-react-native-video/commit/366c841c0b960fd461ae7dcfdcb76a928fadf2b8))
* **android:** check null activity ([c263cc8](https://github.com/nolemonnomelon/nn-react-native-video/commit/c263cc89ff3af5dbab985c24dab31a40d40c8025))
* **android:** clear progress handler before adding new one ([c529f1e](https://github.com/nolemonnomelon/nn-react-native-video/commit/c529f1ecad6a9c1d88bdce4772f337072d8b4df1))
* **android:** contentStartTime default value ([a03c734](https://github.com/nolemonnomelon/nn-react-native-video/commit/a03c7342fbf197d7e349f606fa676829e2b2f1c9))
* **android:** default UA ([#3429](https://github.com/nolemonnomelon/nn-react-native-video/issues/3429)) ([dd7bb54](https://github.com/nolemonnomelon/nn-react-native-video/commit/dd7bb54720c06eca045d72e7557d6f472a793b6f))
* **android:** enableDecoderFallback to decrease DECODER_ERROR issue ([#3416](https://github.com/nolemonnomelon/nn-react-native-video/issues/3416)) ([eaa72c6](https://github.com/nolemonnomelon/nn-react-native-video/commit/eaa72c66659b9e2a22af9ff9d43013521f6a66e3))
* **android:** ensure adTagUrl can be reset ([#3408](https://github.com/nolemonnomelon/nn-react-native-video/issues/3408)) ([f9bcaac](https://github.com/nolemonnomelon/nn-react-native-video/commit/f9bcaac5158ea2d835dd3177b62ad0446eb30d67))
* **android:** ensure audio volume is changed in UI thread ([#3292](https://github.com/nolemonnomelon/nn-react-native-video/issues/3292)) ([0bfbda6](https://github.com/nolemonnomelon/nn-react-native-video/commit/0bfbda66e40a017745584007efe30db95f0f399e))
* **android:** ensure rate is never set to 0 ([#3593](https://github.com/nolemonnomelon/nn-react-native-video/issues/3593)) ([3d7444a](https://github.com/nolemonnomelon/nn-react-native-video/commit/3d7444ab25c365b36e0e8d2672b74f474bba12eb))
* **android:** ensure we don't disable playback when player is ENDED (issue [#2690](https://github.com/nolemonnomelon/nn-react-native-video/issues/2690)) ([b10de93](https://github.com/nolemonnomelon/nn-react-native-video/commit/b10de93128167fad1630fba4d9f18ea2e304fd08))
* **android:** fix crash with interop layer ([#3509](https://github.com/nolemonnomelon/nn-react-native-video/issues/3509)) ([41e9bcb](https://github.com/nolemonnomelon/nn-react-native-video/commit/41e9bcb1ef28c1532863186c83423814fcaf2372))
* **android:** fix leak caused by removing lifecycle listener too early ([#3380](https://github.com/nolemonnomelon/nn-react-native-video/issues/3380)) ([0c0f317](https://github.com/nolemonnomelon/nn-react-native-video/commit/0c0f3174cb37d3c664a345ea00fcbaafffcd4b10))
* **android:** fix tracks selection ([8c95464](https://github.com/nolemonnomelon/nn-react-native-video/commit/8c954647883a72cf8af5de8ac39186ec22a90e34))
* **android:** fixed bug where video would not be visible after remount and change of drm source ([#3668](https://github.com/nolemonnomelon/nn-react-native-video/issues/3668)) ([1af12f9](https://github.com/nolemonnomelon/nn-react-native-video/commit/1af12f9dfb107c58a1896ee3181cb2c1a4fe300f))
* **android:** hide fullscreen button when already in full screen ([973651e](https://github.com/nolemonnomelon/nn-react-native-video/commit/973651e4161be124f7272c9f6427caf3132b3da0))
* **android:** implement live configuration management ([#3792](https://github.com/nolemonnomelon/nn-react-native-video/issues/3792)) ([e16730d](https://github.com/nolemonnomelon/nn-react-native-video/commit/e16730de11d50b8a85cd09fa2b102fdbf777d8ad))
* **android:** implement seek backward in notification service ([#3808](https://github.com/nolemonnomelon/nn-react-native-video/issues/3808)) ([94b3da3](https://github.com/nolemonnomelon/nn-react-native-video/commit/94b3da3477af3d82e4b16e6c93beb5c92ccee59b))
* **android:** improve and backBufferDurationMs. mainly let exoplayer manage the prop ([#3619](https://github.com/nolemonnomelon/nn-react-native-video/issues/3619)) ([f10511d](https://github.com/nolemonnomelon/nn-react-native-video/commit/f10511d9534257a8fc9a4a47978d9c844428f1f7))
* **android:** keep screen on on fullscreen ([#3563](https://github.com/nolemonnomelon/nn-react-native-video/issues/3563)) ([bfb76e6](https://github.com/nolemonnomelon/nn-react-native-video/commit/bfb76e6d15f88a7dc50c63958486375e142a26bd))
* **android:** onSeek called instantly ([#3530](https://github.com/nolemonnomelon/nn-react-native-video/issues/3530)) ([af6aea8](https://github.com/nolemonnomelon/nn-react-native-video/commit/af6aea8934e19467e1ed8e21808b2dbddb6f6356))
* **android:** playback doesn't work with 0 startPositionMs ([#3784](https://github.com/nolemonnomelon/nn-react-native-video/issues/3784)) ([66e0ba5](https://github.com/nolemonnomelon/nn-react-native-video/commit/66e0ba579b84d745b4ca1b076d41d8eb880ef616))
* **android:** poster hidding ([#3768](https://github.com/nolemonnomelon/nn-react-native-video/issues/3768)) ([98b4a75](https://github.com/nolemonnomelon/nn-react-native-video/commit/98b4a75a90c6bc97cde267ea1c6a4a68d0bfdf45))
* **android:** prevent changing video track when video load ([#3683](https://github.com/nolemonnomelon/nn-react-native-video/issues/3683)) ([6f61d7f](https://github.com/nolemonnomelon/nn-react-native-video/commit/6f61d7f6e6969d05e4cee9bdb2e4cbc80d356e7f))
* **android:** random android crash ([#3777](https://github.com/nolemonnomelon/nn-react-native-video/issues/3777)) ([d4c9be2](https://github.com/nolemonnomelon/nn-react-native-video/commit/d4c9be2ba09dd410f0d878ce3f6a1cca987f6713))
* **android:** re-layout controls after fullscreen dismiss ([#3490](https://github.com/nolemonnomelon/nn-react-native-video/issues/3490)) ([135d97c](https://github.com/nolemonnomelon/nn-react-native-video/commit/135d97ce506bf1a0226042e0f29f4de5bcc10972))
* **android:** remove kotlin-android-extensions ([#3299](https://github.com/nolemonnomelon/nn-react-native-video/issues/3299)) ([c78077f](https://github.com/nolemonnomelon/nn-react-native-video/commit/c78077ff0a3e0a2410fbc750ae5f2c0457e9eb22))
* **android:** remove remaining ad view when zapping ([#3786](https://github.com/nolemonnomelon/nn-react-native-video/issues/3786)) ([324b461](https://github.com/nolemonnomelon/nn-react-native-video/commit/324b46152703d813945778f55d87310d4e0b03cf))
* **android:** revert media3 update, back to 1.1.1 ([#3369](https://github.com/nolemonnomelon/nn-react-native-video/issues/3369)) ([5beef38](https://github.com/nolemonnomelon/nn-react-native-video/commit/5beef383cba13d3ac471bfde27e4acfaa19adfec))
* **android:** revert previous fix not compatible with old java version ([#3828](https://github.com/nolemonnomelon/nn-react-native-video/issues/3828)) ([69bde44](https://github.com/nolemonnomelon/nn-react-native-video/commit/69bde447b825507533627c7b7d931e5a5d19ef75))
* **android:** seek callback with controls ([#3694](https://github.com/nolemonnomelon/nn-react-native-video/issues/3694)) ([c730306](https://github.com/nolemonnomelon/nn-react-native-video/commit/c730306e3a408be753febf6e5a6e9c2984a3bbb5))
* **android:** set title for external subtitles ([#3676](https://github.com/nolemonnomelon/nn-react-native-video/issues/3676)) ([336b9f0](https://github.com/nolemonnomelon/nn-react-native-video/commit/336b9f022065b881eb31038ea1adba9dc54b2a08))
* **android:** source metadata compare function ([#3775](https://github.com/nolemonnomelon/nn-react-native-video/issues/3775)) ([6455380](https://github.com/nolemonnomelon/nn-react-native-video/commit/6455380f9e15099b975dce9beaf9b9af8298f998))
* **android:** support opacity properly ([#3464](https://github.com/nolemonnomelon/nn-react-native-video/issues/3464)) ([11e5b75](https://github.com/nolemonnomelon/nn-react-native-video/commit/11e5b756b14a2751352f97cde4fc027f441253ae))
* **android:** suppress lint `PrivateResource` ([#3531](https://github.com/nolemonnomelon/nn-react-native-video/issues/3531)) ([38e3625](https://github.com/nolemonnomelon/nn-react-native-video/commit/38e3625541753340e912e474b753e0f4fac4e9c1))
* **android:** track selection parameter has change in last release. ([#3594](https://github.com/nolemonnomelon/nn-react-native-video/issues/3594)) ([d5c8b51](https://github.com/nolemonnomelon/nn-react-native-video/commit/d5c8b514a1af23fa473f32b434612feac46fd321))
* **android:** update build tools ([89f6c40](https://github.com/nolemonnomelon/nn-react-native-video/commit/89f6c406867487d8efca4f51eff261ebe66c7750))
* **android:** update ui manager getter ([#3634](https://github.com/nolemonnomelon/nn-react-native-video/issues/3634)) ([e87c14a](https://github.com/nolemonnomelon/nn-react-native-video/commit/e87c14a4375d47a03447716b1920608855df5d8d))
* **android:** video flickering add playback start ([#3746](https://github.com/nolemonnomelon/nn-react-native-video/issues/3746)) ([b1cd52b](https://github.com/nolemonnomelon/nn-react-native-video/commit/b1cd52bc58b3dfd02dab4784ea423ebddae874c4))
* **android:** video tracks crash and clean ([#3767](https://github.com/nolemonnomelon/nn-react-native-video/issues/3767)) ([219496f](https://github.com/nolemonnomelon/nn-react-native-video/commit/219496ff3abf6d7362ae01fb66c0bf28dfb00510))
* avoid crash when setting index to 0 to tracks selection ([#3721](https://github.com/nolemonnomelon/nn-react-native-video/issues/3721)) ([518a9a9](https://github.com/nolemonnomelon/nn-react-native-video/commit/518a9a93e06686ba707427078a1770dc3d803b2b))
* **avoid:** avoid early return in setSrc ([#3759](https://github.com/nolemonnomelon/nn-react-native-video/issues/3759)) ([2e623ca](https://github.com/nolemonnomelon/nn-react-native-video/commit/2e623ca0fb074e64a6125994effb8723f5c4ce59))
* **ci/docs:** fix docs deploy ([#3317](https://github.com/nolemonnomelon/nn-react-native-video/issues/3317)) ([9ba1ca6](https://github.com/nolemonnomelon/nn-react-native-video/commit/9ba1ca6c32d2148439e21f44feb7949fb89cb2ff))
* **ci:** bump node version ([#3289](https://github.com/nolemonnomelon/nn-react-native-video/issues/3289)) ([03a579e](https://github.com/nolemonnomelon/nn-react-native-video/commit/03a579e10f41b1d9f1e1a7b22caf79b1a4cd6785))
* disable Google IMA by default on ios. now shall be enabled in project podfile ([4aca30d](https://github.com/nolemonnomelon/nn-react-native-video/commit/4aca30d308e33d0e6410caabd5fcafd8b996ec7a))
* **docs/ci:** add typescript ([#3572](https://github.com/nolemonnomelon/nn-react-native-video/issues/3572)) ([0f31271](https://github.com/nolemonnomelon/nn-react-native-video/commit/0f31271dcf2bfe2f4429e22040660025be8a6a3c))
* **docs:** fix build ([#3571](https://github.com/nolemonnomelon/nn-react-native-video/issues/3571)) ([4fc7d27](https://github.com/nolemonnomelon/nn-react-native-video/commit/4fc7d2788b4d01c581a31cc3ac733c3948b65a3a))
* ensure player receive uri update event if the uri is empty ([3f44d6e](https://github.com/nolemonnomelon/nn-react-native-video/commit/3f44d6ee253ab527ad914360079df2000a5c9563))
* ensure poster works as expected and add it to the sample ([#3643](https://github.com/nolemonnomelon/nn-react-native-video/issues/3643)) ([d694139](https://github.com/nolemonnomelon/nn-react-native-video/commit/d6941392e071f2bd50fbe832dde203b7f18da769))
* ensure save doesn't crash on android ([#3415](https://github.com/nolemonnomelon/nn-react-native-video/issues/3415)) ([22a2655](https://github.com/nolemonnomelon/nn-react-native-video/commit/22a2655dca4bb53074ce5a74cfeb7f9bb26b13a3))
* ensure tracks are available in sample ([#3660](https://github.com/nolemonnomelon/nn-react-native-video/issues/3660)) ([4c7719a](https://github.com/nolemonnomelon/nn-react-native-video/commit/4c7719a3f537509426c366d2176895661933c63c))
* **example:** remove dependency loop ([#3353](https://github.com/nolemonnomelon/nn-react-native-video/issues/3353)) ([211c3c7](https://github.com/nolemonnomelon/nn-react-native-video/commit/211c3c7d08c8438bfca3350f0070cfec0ae5bc56))
* **example:** update metro config ([#3291](https://github.com/nolemonnomelon/nn-react-native-video/issues/3291)) ([45dcded](https://github.com/nolemonnomelon/nn-react-native-video/commit/45dcded5762d258248c77001a70e431e3be982c8))
* **exoplayer:** allow uri to high case ([f4f9e28](https://github.com/nolemonnomelon/nn-react-native-video/commit/f4f9e28fb1a67ba6b14c257d029da166b85f3ae6))
* **exoplayer:** ensure player is stopped when invalid uri is configured ([f31e47f](https://github.com/nolemonnomelon/nn-react-native-video/commit/f31e47f36007a3d75f76eb454b051597bd9d12df))
* fix bad package release process ([#3347](https://github.com/nolemonnomelon/nn-react-native-video/issues/3347)) ([f961f95](https://github.com/nolemonnomelon/nn-react-native-video/commit/f961f952a483192ee3de1f7bae59419ec6ddc5b7))
* fix build on xcode 17 beta ([a18953e](https://github.com/nolemonnomelon/nn-react-native-video/commit/a18953e701fbc8a52632c6f5420117c3154610ff))
* fix code block in README.md ([#1455](https://github.com/nolemonnomelon/nn-react-native-video/issues/1455)) ([80391d4](https://github.com/nolemonnomelon/nn-react-native-video/commit/80391d4e2ae639bb4079b2595a5d7ca27ebaeb7b))
* fix codegen types ([#3636](https://github.com/nolemonnomelon/nn-react-native-video/issues/3636)) ([9b66e7f](https://github.com/nolemonnomelon/nn-react-native-video/commit/9b66e7fdce0393c4e2154a23b407de6c46dc9490))
* fix control not showing up at very first touch ([a79c30e](https://github.com/nolemonnomelon/nn-react-native-video/commit/a79c30eaba277db4cd13b3515567c17b7a09ee58))
* fix getLicense function's type definition ([#3606](https://github.com/nolemonnomelon/nn-react-native-video/issues/3606)) ([89ae843](https://github.com/nolemonnomelon/nn-react-native-video/commit/89ae8438fa1d90700a462b117aa9af42780c6268))
* fix ios compile issue ([0d6c507](https://github.com/nolemonnomelon/nn-react-native-video/commit/0d6c50756cc657b52a1c758a9722c0300c30685d))
* fix memory leak for iOS ([86a89ea](https://github.com/nolemonnomelon/nn-react-native-video/commit/86a89eaed2fe5f7f81ebbb43419936b417781324))
* fix the default behaviour ([f0c40f9](https://github.com/nolemonnomelon/nn-react-native-video/commit/f0c40f939200a1099c58ece3ec8c3dca63e41173))
* fix the hardware back button ([622f9d3](https://github.com/nolemonnomelon/nn-react-native-video/commit/622f9d3f3f2d5bb2bb5568eee740f2972685f255))
* fix the kvo compliance crash when rapidly switching source ([1f27ffb](https://github.com/nolemonnomelon/nn-react-native-video/commit/1f27ffbc8101044eb59866886fec6fd12223febf))
* fix the play button no shown after pausing video at the very first time ([f7aeb72](https://github.com/nolemonnomelon/nn-react-native-video/commit/f7aeb7295064631d2c45e95ec8013ea6289e36c9))
* fix the system status bar when dismiss ([2a77c5f](https://github.com/nolemonnomelon/nn-react-native-video/commit/2a77c5f0df28f52a7bb7df90c0d23f4b0f51dbca))
* fix the wrong merge conflict ([ee1217d](https://github.com/nolemonnomelon/nn-react-native-video/commit/ee1217d95ecb13bc913599dff762018dd14b49c1))
* fix tvos available compile errors ([fd2e396](https://github.com/nolemonnomelon/nn-react-native-video/commit/fd2e396262a1ce662c4e33229dcc97dd40591a11))
* fix tvos available compile errors ([a7a0390](https://github.com/nolemonnomelon/nn-react-native-video/commit/a7a03901f2d65da8d956c34d3df82d87efc4a169))
* fix typo ([#3497](https://github.com/nolemonnomelon/nn-react-native-video/issues/3497)) ([336eb44](https://github.com/nolemonnomelon/nn-react-native-video/commit/336eb44dc6061dad9cdc3382eb05d0a0effbef64))
* fixes where Android's muted prop behavior differs from iOS ([#3339](https://github.com/nolemonnomelon/nn-react-native-video/issues/3339)) ([8fbdc28](https://github.com/nolemonnomelon/nn-react-native-video/commit/8fbdc28a73a0b3ffd3691ef0c8cf523c760ae288))
* handle the initial fullscreen props ([5203fa6](https://github.com/nolemonnomelon/nn-react-native-video/commit/5203fa63d49c6c503b4e4dac4a97ec1241b75ea2))
* implement lost presentFullscreenPlayer & dismissFullscreenPlayer ([ddc87ac](https://github.com/nolemonnomelon/nn-react-native-video/commit/ddc87acf840f4d0e451e7f1c7bd1f9f2912636a5))
* improve basic player ([3d40461](https://github.com/nolemonnomelon/nn-react-native-video/commit/3d40461a32dcdc9f7b1d9dd44102746f094e9adb))
* improve initial test for checking url validity ([d67b3c4](https://github.com/nolemonnomelon/nn-react-native-video/commit/d67b3c45b5fc01c6e4c03b8e056eaf79f1accebe))
* inject onGetLicense prop properly for detect user defined or not ([#3608](https://github.com/nolemonnomelon/nn-react-native-video/issues/3608)) ([24c1aab](https://github.com/nolemonnomelon/nn-react-native-video/commit/24c1aab3f5ab6d2d753199ea16e01c993cc3ef7d))
* invalid doc path ([f990ec9](https://github.com/nolemonnomelon/nn-react-native-video/commit/f990ec9de12977d87673f587b72d0987d6c61a0b))
* ios build error due to missing push ([2a69c16](https://github.com/nolemonnomelon/nn-react-native-video/commit/2a69c16264d062048f4d22e7f3450388ff8c98c8))
* **ios:** add text tracks only if we successfully insertTimeRage ([#3557](https://github.com/nolemonnomelon/nn-react-native-video/issues/3557)) ([b73baad](https://github.com/nolemonnomelon/nn-react-native-video/commit/b73baad2c2c0c6ea701d865eee32d4e94ae58178))
* **ios:** add workaround for `TouchableWithoutFeedback` ([#3688](https://github.com/nolemonnomelon/nn-react-native-video/issues/3688)) ([b5ccc48](https://github.com/nolemonnomelon/nn-react-native-video/commit/b5ccc48476d958f6b70d8a163a8d1209d1c3c302))
* **ios:** apply `cropStart` when in repeat mode ([#3525](https://github.com/nolemonnomelon/nn-react-native-video/issues/3525)) ([2c0e009](https://github.com/nolemonnomelon/nn-react-native-video/commit/2c0e00987685875f9603ae2084ae23b3c1aebce7))
* **ios:** apply PictureInPicture state on start ([#3655](https://github.com/nolemonnomelon/nn-react-native-video/issues/3655)) ([07f71c2](https://github.com/nolemonnomelon/nn-react-native-video/commit/07f71c2fc446b43aa9565659983f7acb36d95f0c))
* **ios:** call `onLoadStart` earlier ([#3750](https://github.com/nolemonnomelon/nn-react-native-video/issues/3750)) ([b3f08f6](https://github.com/nolemonnomelon/nn-react-native-video/commit/b3f08f6c990f4670311e6d918aea191e72673057))
* **ios:** call PictureInPicture callbacks with native controls ([#3603](https://github.com/nolemonnomelon/nn-react-native-video/issues/3603)) ([051e884](https://github.com/nolemonnomelon/nn-react-native-video/commit/051e884c8f34755c887b66d8715a6ee38efc5f77)), closes [#3602](https://github.com/nolemonnomelon/nn-react-native-video/issues/3602) [#3602](https://github.com/nolemonnomelon/nn-react-native-video/issues/3602)
* **ios:** change isPlaybackLikelyToKeepUp check ([#3357](https://github.com/nolemonnomelon/nn-react-native-video/issues/3357)) ([1ba93f9](https://github.com/nolemonnomelon/nn-react-native-video/commit/1ba93f9e9d33f653f0e01214f220e1e5eda819f5))
* **ios:** check for ios url query encoding ([#3384](https://github.com/nolemonnomelon/nn-react-native-video/issues/3384)) ([de4159f](https://github.com/nolemonnomelon/nn-react-native-video/commit/de4159f0c2825a58d88f3882215da4bf51fdbeb2))
* **ios:** crash due to persistent keyPath observer ([#600](https://github.com/nolemonnomelon/nn-react-native-video/issues/600)) ([093ffcc](https://github.com/nolemonnomelon/nn-react-native-video/commit/093ffccd9b99f5b1de10832f01cda895bcb64a3a))
* **ios:** current release volume change observer ([#3565](https://github.com/nolemonnomelon/nn-react-native-video/issues/3565)) ([16f3cdb](https://github.com/nolemonnomelon/nn-react-native-video/commit/16f3cdbd9a7864206feaeef29344c09792d66d56))
* **ios:** currentPlaybackTime in ms and not seconds ([#3472](https://github.com/nolemonnomelon/nn-react-native-video/issues/3472)) ([3f63c16](https://github.com/nolemonnomelon/nn-react-native-video/commit/3f63c161ebf66232ae4f4caeacd6ad8454820a9d))
* **ios:** destroy adsManager when player detach from super view ([#3716](https://github.com/nolemonnomelon/nn-react-native-video/issues/3716)) ([#3722](https://github.com/nolemonnomelon/nn-react-native-video/issues/3722)) ([e96c173](https://github.com/nolemonnomelon/nn-react-native-video/commit/e96c17321f1347818c1f5a38628d65b5b4bd5e7b))
* **ios:** Do not crash when accessLog return nil ([#3549](https://github.com/nolemonnomelon/nn-react-native-video/issues/3549)) ([4d4b56c](https://github.com/nolemonnomelon/nn-react-native-video/commit/4d4b56c05dd3c09fce5ddc38f56b0391c357ac85))
* **ios:** do not save pause state before seeking ([#3650](https://github.com/nolemonnomelon/nn-react-native-video/issues/3650)) ([e992243](https://github.com/nolemonnomelon/nn-react-native-video/commit/e992243305af0915442c3400f6ef105c4d5cd44c))
* **ios:** don't crop video when in repeat mode ([#3575](https://github.com/nolemonnomelon/nn-react-native-video/issues/3575)) ([90b31af](https://github.com/nolemonnomelon/nn-react-native-video/commit/90b31af2c969b6d6d57877c71ef3a4830a76aedc))
* **ios:** ensure audio and subtitle tracks are well reported ([0e0ff18](https://github.com/nolemonnomelon/nn-react-native-video/commit/0e0ff18b279f7f0646129adab182435794d8cd4b))
* **ios:** ensure controls are not displayed when disabled by user ([2032a36](https://github.com/nolemonnomelon/nn-react-native-video/commit/2032a36969a022c57232baa8f3b9746eff103c28))
* **ios:** ensure duration available when playing live ([#3710](https://github.com/nolemonnomelon/nn-react-native-video/issues/3710)) ([d56b251](https://github.com/nolemonnomelon/nn-react-native-video/commit/d56b251aef6d4ca1708c7bbada15016efbf12caf))
* **ios:** ensure orientation is correct on iOS ([#3719](https://github.com/nolemonnomelon/nn-react-native-video/issues/3719)) ([1a8295c](https://github.com/nolemonnomelon/nn-react-native-video/commit/1a8295c8bf30d53135d723fc9aface1a812be78a))
* **ios:** ensure playback stopped in background ([#3587](https://github.com/nolemonnomelon/nn-react-native-video/issues/3587)) ([41c6785](https://github.com/nolemonnomelon/nn-react-native-video/commit/41c6785ee8c667ebe9c6c464223f6485473d94f8))
* **ios:** ensure we stop playback on invalid or empty url ([2efa746](https://github.com/nolemonnomelon/nn-react-native-video/commit/2efa746eed85eb2b4fd1df2e119b407d9fb1b9a2))
* **ios:** fairplay different key per asset ([#3261](https://github.com/nolemonnomelon/nn-react-native-video/issues/3261)) ([f4acacc](https://github.com/nolemonnomelon/nn-react-native-video/commit/f4acaccd80a3e380940d014d18cda3d03d5720c2))
* **ios:** fix cache playerItemPrepareText type ([#3358](https://github.com/nolemonnomelon/nn-react-native-video/issues/3358)) ([0e23952](https://github.com/nolemonnomelon/nn-react-native-video/commit/0e23952cea5c71324a2f5eea0383c4db9e02504b))
* **ios:** fix external text tracks crashes with m3u8 files ([#3330](https://github.com/nolemonnomelon/nn-react-native-video/issues/3330)) ([782e7e0](https://github.com/nolemonnomelon/nn-react-native-video/commit/782e7e0df1386ef0aad3f00d73171d04d6cf725d))
* **iOS:** fix iOS DRM header parser ([#3609](https://github.com/nolemonnomelon/nn-react-native-video/issues/3609)) ([c9a75f3](https://github.com/nolemonnomelon/nn-react-native-video/commit/c9a75f3cde82f55e612b9e2c30ca06db3093b283))
* **ios:** fix missing bridge in bridgeless mode ([#3570](https://github.com/nolemonnomelon/nn-react-native-video/issues/3570)) ([46c8c49](https://github.com/nolemonnomelon/nn-react-native-video/commit/46c8c498c474600a0b35ebaf744306aefa42905f))
* **ios:** fix PiP callback ([#3601](https://github.com/nolemonnomelon/nn-react-native-video/issues/3601)) ([bb9e7eb](https://github.com/nolemonnomelon/nn-react-native-video/commit/bb9e7eb5a5d68de1d8945be2f3fa089ca6ce2465))
* **ios:** fix pip memory leak ([#3506](https://github.com/nolemonnomelon/nn-react-native-video/issues/3506)) ([53068dd](https://github.com/nolemonnomelon/nn-react-native-video/commit/53068ddd41218bb615cd129eba2c36d6347ccf25))
* **ios:** fix pip(when player doesn't fill screen) ([#3363](https://github.com/nolemonnomelon/nn-react-native-video/issues/3363)) ([11f6201](https://github.com/nolemonnomelon/nn-react-native-video/commit/11f62013e33939ce3f78ec7cf40e4da464afa824))
* **ios:** fix regression when playing source starting with ph:// ([#3630](https://github.com/nolemonnomelon/nn-react-native-video/issues/3630)) ([75d3707](https://github.com/nolemonnomelon/nn-react-native-video/commit/75d370742b95ddf0eb114ef48620e188e6fdfad1))
* **ios:** fix sideloading external subtitles ([#3690](https://github.com/nolemonnomelon/nn-react-native-video/issues/3690)) ([efa1c52](https://github.com/nolemonnomelon/nn-react-native-video/commit/efa1c52491cb069f6f4ba92ba56cf38624fecfde))
* **ios:** fix startPosition, cropStart and cropEnd to handle float values correctly ([#3589](https://github.com/nolemonnomelon/nn-react-native-video/issues/3589)) ([36bd2e2](https://github.com/nolemonnomelon/nn-react-native-video/commit/36bd2e2d71dc6879d74b154ecc39ea7b27f4b565))
* **ios:** fix text track selection by index ([#3728](https://github.com/nolemonnomelon/nn-react-native-video/issues/3728)) ([51e22ab](https://github.com/nolemonnomelon/nn-react-native-video/commit/51e22abfe35978ee3fd1a7b3dc6f6c769d1b24bc))
* **ios:** fix tvOS build ([#3524](https://github.com/nolemonnomelon/nn-react-native-video/issues/3524)) ([9306d9a](https://github.com/nolemonnomelon/nn-react-native-video/commit/9306d9a15d281a60492f6d4166598a389a56f652))
* **ios:** fix wrong fullscreen method definition ([#3338](https://github.com/nolemonnomelon/nn-react-native-video/issues/3338)) ([7f49b56](https://github.com/nolemonnomelon/nn-react-native-video/commit/7f49b560278262fb4276f931404c70672a6445c8))
* **ios:** message sent to deallocated instance ([#1482](https://github.com/nolemonnomelon/nn-react-native-video/issues/1482)) ([d8a2a9e](https://github.com/nolemonnomelon/nn-react-native-video/commit/d8a2a9e108c52e79b850be17bff08e1519c118ea))
* **ios:** player is frozen after re-focusing on the app ([#3326](https://github.com/nolemonnomelon/nn-react-native-video/issues/3326)) ([722ae34](https://github.com/nolemonnomelon/nn-react-native-video/commit/722ae3477a68aecb812b26d71ea22a17dda71f50))
* **ios:** remove extra dismissFullscreenPlayer declaration ([#3474](https://github.com/nolemonnomelon/nn-react-native-video/issues/3474)) ([045f5fa](https://github.com/nolemonnomelon/nn-react-native-video/commit/045f5fa0080eb7793b288311ff5366c1198f19f1))
* **ios:** remove false calls at `onPlaybackRateChange` ([#3306](https://github.com/nolemonnomelon/nn-react-native-video/issues/3306)) ([286418e](https://github.com/nolemonnomelon/nn-react-native-video/commit/286418e4a5a4331257d39012b0ef9d4d17519af8))
* **ios:** resuming video ad after closing the in-app browser on iOS ([#3275](https://github.com/nolemonnomelon/nn-react-native-video/issues/3275)) ([e6e8f62](https://github.com/nolemonnomelon/nn-react-native-video/commit/e6e8f621fe03b6b027197ef91fff78ed49dce2cb))
* **ios:** revert ios url encoding as this breaks encoded urls ([#3440](https://github.com/nolemonnomelon/nn-react-native-video/issues/3440)) ([0723481](https://github.com/nolemonnomelon/nn-react-native-video/commit/0723481fee75890bc2fff967e3b5bc8946e481a3))
* **iOS:** sometimes aspect ratio is invalid ([#3821](https://github.com/nolemonnomelon/nn-react-native-video/issues/3821)) ([dac0985](https://github.com/nolemonnomelon/nn-react-native-video/commit/dac09854303335d8e37b633c37bca399499d1999))
* **ios:** split licenseUrl and loadedLicenseUrl ([#3578](https://github.com/nolemonnomelon/nn-react-native-video/issues/3578)) ([7c4d19f](https://github.com/nolemonnomelon/nn-react-native-video/commit/7c4d19fa72a35449dd11ec59278b2ea11ec629fc))
* **iOS:** throw when content id defined with empty string ([#3612](https://github.com/nolemonnomelon/nn-react-native-video/issues/3612)) ([0983580](https://github.com/nolemonnomelon/nn-react-native-video/commit/098358076ddaba387284c1757a80bfcc5d82191f))
* **ios:** update onPlaybackStateChanged implementation ([#3687](https://github.com/nolemonnomelon/nn-react-native-video/issues/3687)) ([042e13c](https://github.com/nolemonnomelon/nn-react-native-video/commit/042e13c1dc3f88a42cd9293b064f9cebacecc831))
* **ios:** workaround for rate change ([#3657](https://github.com/nolemonnomelon/nn-react-native-video/issues/3657)) ([e26afac](https://github.com/nolemonnomelon/nn-react-native-video/commit/e26afac403e0b3675138f18569b08b4c9000cd81))
* issue 3040, prevent crash ([d526479](https://github.com/nolemonnomelon/nn-react-native-video/commit/d526479fe0983cbd1aa1a4a6ab1dd1ba82e85bb7))
* issue 3085, onFullscreen call backs are never fired ([238daf8](https://github.com/nolemonnomelon/nn-react-native-video/commit/238daf8720ab6c1a4a53004b3dbd93c0be47f3ba))
* **js:** fix onPlaybackStateChanged callback ([#3753](https://github.com/nolemonnomelon/nn-react-native-video/issues/3753)) ([f87a793](https://github.com/nolemonnomelon/nn-react-native-video/commit/f87a7938c6941c69915477fcf5f08c54a2635597))
* memory leak due to [weak self] and delegate not being weak ([50b3650](https://github.com/nolemonnomelon/nn-react-native-video/commit/50b3650e2fe5a2624559f50bc81f4481be2475ee))
* move basic sample to typescript ([a0c9b4e](https://github.com/nolemonnomelon/nn-react-native-video/commit/a0c9b4e09054430a852f8dfec97caf934a57f832))
* not showing video ads in pip mode ([59236c7](https://github.com/nolemonnomelon/nn-react-native-video/commit/59236c7034132eaa22fe0f86da8f77ed08b05d58))
* omit packager assets from caching ([#1438](https://github.com/nolemonnomelon/nn-react-native-video/issues/1438)) ([125d5dc](https://github.com/nolemonnomelon/nn-react-native-video/commit/125d5dc9c54dd243742a204746b5a227d7b1e723))
* prevents crash from occurring when using the selected video track with resolution type ([#3664](https://github.com/nolemonnomelon/nn-react-native-video/issues/3664)) ([e82f9dc](https://github.com/nolemonnomelon/nn-react-native-video/commit/e82f9dc24b6a4a09786f5425153b53494d72b05d))
* **RCTVideo.m:** Fixed status bar disappearing issue ([3ef9555](https://github.com/nolemonnomelon/nn-react-native-video/commit/3ef955546412c7ea2017ac4cc742dc9bca51f724))
* **ReactVideoProps:** add accessibility & testID in typing ([#3434](https://github.com/nolemonnomelon/nn-react-native-video/issues/3434)) ([d986b7b](https://github.com/nolemonnomelon/nn-react-native-video/commit/d986b7bf57f8fe49cbf5f507efde4aeb28ee34f8))
* refactor full screen button visibility update ([55209b4](https://github.com/nolemonnomelon/nn-react-native-video/commit/55209b48c04ef01ef6593972c8313d61abfceb21))
* refactor fullScreenPlayerView creation ([a323bd0](https://github.com/nolemonnomelon/nn-react-native-video/commit/a323bd0523eff8c68940e7fbe6aca254679adf96))
* remove `setNativeProps` usage ([#3605](https://github.com/nolemonnomelon/nn-react-native-video/issues/3605)) ([0312afc](https://github.com/nolemonnomelon/nn-react-native-video/commit/0312afc8ea27f8c82ef7ba9fecbde23174e68671))
* remove dummy nativeOnly ([aaa9612](https://github.com/nolemonnomelon/nn-react-native-video/commit/aaa961296b3d735ffaa0be480703a395b8de383d))
* remove dummy needsToRestoreUserInterfaceForPictureInPictureStop ([822f8c0](https://github.com/nolemonnomelon/nn-react-native-video/commit/822f8c077476383fbadd2a47c3c4d27d9f8ee082))
* remove dummy scaleX/Y & translateX/Y property ([d9e4b1e](https://github.com/nolemonnomelon/nn-react-native-video/commit/d9e4b1efecd3cc2f6092e0e541e886403f59e849))
* remove lifecycle listener after component unmount ([#3489](https://github.com/nolemonnomelon/nn-react-native-video/issues/3489)) ([3858a15](https://github.com/nolemonnomelon/nn-react-native-video/commit/3858a15b4268ae54d5b97c036d86b05aaf31bcf9)), closes [#3488](https://github.com/nolemonnomelon/nn-react-native-video/issues/3488)
* remove pausePlayback when audio focus loss event ([#3496](https://github.com/nolemonnomelon/nn-react-native-video/issues/3496)) ([b1ab0f2](https://github.com/nolemonnomelon/nn-react-native-video/commit/b1ab0f24a3efbcc3be49005060f50b34a117664e))
* remove runtime warning by replacing `UIManager.RCTVideo` with `UIManager.getViewManagerConfig('RCTVideo')` (and ensuring backwards compat) ([#1487](https://github.com/nolemonnomelon/nn-react-native-video/issues/1487)) ([b448b30](https://github.com/nolemonnomelon/nn-react-native-video/commit/b448b30de65c3194c7f4e1189a89e1e976a42091))
* remove undocumented currentTime property ([2ef2b8e](https://github.com/nolemonnomelon/nn-react-native-video/commit/2ef2b8eb98b96adb5f8cd645686a5ba7f8a628bc))
* revert drm type definition change ([#3409](https://github.com/nolemonnomelon/nn-react-native-video/issues/3409)) ([fbb5654](https://github.com/nolemonnomelon/nn-react-native-video/commit/fbb5654a8e075a2b33ae17bd322bb79b1f459d53))
* review safety checks ([53fe197](https://github.com/nolemonnomelon/nn-react-native-video/commit/53fe1973e5c47589601ccc8be56fecb42ab5beb3))
* runtime issue ([b0e25be](https://github.com/nolemonnomelon/nn-react-native-video/commit/b0e25bea8fdb4d1b7fa8f910fd3e0efaf9e136ac))
* set the correct git url ([#1439](https://github.com/nolemonnomelon/nn-react-native-video/issues/1439)) ([4dc4db3](https://github.com/nolemonnomelon/nn-react-native-video/commit/4dc4db3a83d725264fb0b181ce2a8a73e9707ef2))
* **texttracks:** unable to disable sideloaded texttracks in the AVPlayer ([c9ecc8e](https://github.com/nolemonnomelon/nn-react-native-video/commit/c9ecc8e9e03cb68b82ffba6f105f7e282d389de1))
* **ts:** add missing type ([#3757](https://github.com/nolemonnomelon/nn-react-native-video/issues/3757)) ([2d94844](https://github.com/nolemonnomelon/nn-react-native-video/commit/2d9484499cfb58d86b0aa82872d494a03fe67bba))
* **ts:** onPlaybackRateChangeData was not correctly typed ([#3651](https://github.com/nolemonnomelon/nn-react-native-video/issues/3651)) ([2a858df](https://github.com/nolemonnomelon/nn-react-native-video/commit/2a858df8bce4dd6c529853bba5bac85f798c662e))
* **tvOS:** compile issues with tvOS linked to earpiece & pip ([#3276](https://github.com/nolemonnomelon/nn-react-native-video/issues/3276)) ([7b6b84c](https://github.com/nolemonnomelon/nn-react-native-video/commit/7b6b84c8cbb8ec4f1cc8dca53d2b4cb5067576a8))
* **tvos:** fix tvOS build and sample ([#3785](https://github.com/nolemonnomelon/nn-react-native-video/issues/3785)) ([cd42dd7](https://github.com/nolemonnomelon/nn-react-native-video/commit/cd42dd78c96e20da377c9b05c321218f1411ba97))
* update debug JSBundle name & rootView component ([9baa139](https://github.com/nolemonnomelon/nn-react-native-video/commit/9baa1391ca54d321a9717514adfbae25f9984bf1))
* update onError definition to match implementation ([#3349](https://github.com/nolemonnomelon/nn-react-native-video/issues/3349)) ([fdbd6a6](https://github.com/nolemonnomelon/nn-react-native-video/commit/fdbd6a6ba8aef2da854ff7b0fbf25085ce6983e3))
* update types ([#3288](https://github.com/nolemonnomelon/nn-react-native-video/issues/3288)) ([5c3baca](https://github.com/nolemonnomelon/nn-react-native-video/commit/5c3baca1d85bfc8326fb22a8db68b91459b40c41))
* upgrade react-native version on basic sample ([58c719c](https://github.com/nolemonnomelon/nn-react-native-video/commit/58c719c275c5ea29b2b670951ca58ec7fa84f2b7))
* Xcode 12 compatibility ([#2152](https://github.com/nolemonnomelon/nn-react-native-video/issues/2152)) ([f653589](https://github.com/nolemonnomelon/nn-react-native-video/commit/f653589ecd636e35f0535eb105224b6ea0221ff3)), closes [facebook/react-native#29633](https://github.com/facebook/react-native/issues/29633)


### Features

* :zap: added .nvmrc ([183c818](https://github.com/nolemonnomelon/nn-react-native-video/commit/183c818d53e444c4c34bbc3d47c7f82ceef77027))
* :zap: added example video ([9e9c5ec](https://github.com/nolemonnomelon/nn-react-native-video/commit/9e9c5ec01aa847989647e53d494c0e433196d121))
* :zap: added gitignore ([0ea4ac8](https://github.com/nolemonnomelon/nn-react-native-video/commit/0ea4ac883728277ff5b5c074f88daf6c21eac3f6))
* :zap: added laftel video example app ([617bcb3](https://github.com/nolemonnomelon/nn-react-native-video/commit/617bcb36a2160a7eb6e61d2e8474c1fe990f147e))
* :zap: added setup for exapmle ([70bab9e](https://github.com/nolemonnomelon/nn-react-native-video/commit/70bab9e69ca0201e8b3b0167a113dfd6e41a891f))
* :zap: modified setup ([4ddecbf](https://github.com/nolemonnomelon/nn-react-native-video/commit/4ddecbf42b88b6d7e2ec993f57a310591c801161))
* :zap: modified setup ([f5dc499](https://github.com/nolemonnomelon/nn-react-native-video/commit/f5dc4992fbae54fe5156163f88e7a90fc5df1117))
* :zap: Pod install ([fe4e2bf](https://github.com/nolemonnomelon/nn-react-native-video/commit/fe4e2bfcd98d0ea3a9078bccaadb1c9e2920b14a))
* :zap: set path ([f9fe2b0](https://github.com/nolemonnomelon/nn-react-native-video/commit/f9fe2b0f3885c5e97d87052c1782d56f3d9b2e0e))
* :zap: setup android example app for fabric android ([650b3a6](https://github.com/nolemonnomelon/nn-react-native-video/commit/650b3a6a24b5feb175400267fcc389efff9e99d8))
* :zap: setup example app new arch ([7b6e76e](https://github.com/nolemonnomelon/nn-react-native-video/commit/7b6e76e2d05dc0c3f81db7d49c438c3d9e80015e))
* :zap: setup kotlin ([0ca348f](https://github.com/nolemonnomelon/nn-react-native-video/commit/0ca348f4b58b1e5bc0735c02a011e3b05e8f715a))
* :zap: turn on newarch enabled on example app ([0be9de9](https://github.com/nolemonnomelon/nn-react-native-video/commit/0be9de98d837c3ebfd0b9bdb17e66706c0bd1ea5))
* 🎸 add exception catch ([cee650c](https://github.com/nolemonnomelon/nn-react-native-video/commit/cee650c84cb37f31b2596ae1181ea36f0c80bb5b))
* **ad:** add data to onReceiveAdEvent ([#3378](https://github.com/nolemonnomelon/nn-react-native-video/issues/3378)) ([d05231d](https://github.com/nolemonnomelon/nn-react-native-video/commit/d05231d76b87e2f65bc7648bfb81d01e4054b2de))
* add `onVolumeChange` event ([#3322](https://github.com/nolemonnomelon/nn-react-native-video/issues/3322)) ([cdbc856](https://github.com/nolemonnomelon/nn-react-native-video/commit/cdbc85638789da0002cdadb13190963d4c1332c2))
* add AdEvent enum to have an exhaustive list of all possible AdEvent values ([#3374](https://github.com/nolemonnomelon/nn-react-native-video/issues/3374)) ([b3744f9](https://github.com/nolemonnomelon/nn-react-native-video/commit/b3744f9b9f25b469fb8b0828e3762842bd5026de))
* add full screen support based on expo-av implementation ([b144a50](https://github.com/nolemonnomelon/nn-react-native-video/commit/b144a50f41bdc6ea389767f8c4d0076d773aee70))
* add notification controls ([#3723](https://github.com/nolemonnomelon/nn-react-native-video/issues/3723)) ([8ad4be4](https://github.com/nolemonnomelon/nn-react-native-video/commit/8ad4be459b935e30077e38cce696875ea9d6b21f))
* add onAdError event listener ([#3381](https://github.com/nolemonnomelon/nn-react-native-video/issues/3381)) ([596c02d](https://github.com/nolemonnomelon/nn-react-native-video/commit/596c02d2b3b5175e1653844c39a47ecfd5e23163))
* add release-it ([#3342](https://github.com/nolemonnomelon/nn-react-native-video/issues/3342)) ([da27089](https://github.com/nolemonnomelon/nn-react-native-video/commit/da270891fbce485bb132825a336638f2af98408d))
* add setVolume function to component's ref ([#3794](https://github.com/nolemonnomelon/nn-react-native-video/issues/3794)) ([3cd7ab6](https://github.com/nolemonnomelon/nn-react-native-video/commit/3cd7ab60b27e8820607bd83a5681bc7ba7e6c52e))
* add support of subtitles style configuration ([b64c7db](https://github.com/nolemonnomelon/nn-react-native-video/commit/b64c7dbea5f0d9479267e10d1c125dc26cb66dd8))
* add typescript ([#3266](https://github.com/nolemonnomelon/nn-react-native-video/issues/3266)) ([92831af](https://github.com/nolemonnomelon/nn-react-native-video/commit/92831afd5f9b1fcc5d02923aeb04ff4cf1e14889))
* add visionOS support ([#3425](https://github.com/nolemonnomelon/nn-react-native-video/issues/3425)) ([cf3ebb7](https://github.com/nolemonnomelon/nn-react-native-video/commit/cf3ebb7f1520e68fbe72774d1e9f2c33e273e0c4))
* **android:** add new apis to query device capabilities ([3a4cb7f](https://github.com/nolemonnomelon/nn-react-native-video/commit/3a4cb7f6d939a85d2c6118c821f3dc8970dee115))
* **android:** add new events for audioTrack, textTracks and videoTracks ([63008ce](https://github.com/nolemonnomelon/nn-react-native-video/commit/63008ced4282d36d30793e8a8d5f77c0b875d1b4))
* **android:** add playback functions to ref ([0066ec7](https://github.com/nolemonnomelon/nn-react-native-video/commit/0066ec744c5acf5f32a46fa3c74fcd8bf52b0722))
* **android:** add possibility to hide seekBar ([#3789](https://github.com/nolemonnomelon/nn-react-native-video/issues/3789)) ([95e6140](https://github.com/nolemonnomelon/nn-react-native-video/commit/95e6140eead56efab83871e29b57d30f4f11a77a))
* **android:** add prop to control debug log level ([#3277](https://github.com/nolemonnomelon/nn-react-native-video/issues/3277)) ([add8792](https://github.com/nolemonnomelon/nn-react-native-video/commit/add87922a60b53a648131f09c2ec6dd672694676))
* **android:** add sample to test decoder capabilities ([8408664](https://github.com/nolemonnomelon/nn-react-native-video/commit/8408664600d4b1316bcac13e1d50756b84074cf1))
* **android:** add subtitle event ([#3566](https://github.com/nolemonnomelon/nn-react-native-video/issues/3566)) ([6184c10](https://github.com/nolemonnomelon/nn-react-native-video/commit/6184c10acc90defd63cd55af51458864dfe112d5))
* **android:** allow to disable selected functionalities  ([#3681](https://github.com/nolemonnomelon/nn-react-native-video/issues/3681)) ([64e3191](https://github.com/nolemonnomelon/nn-react-native-video/commit/64e3191f73c828067094031a55e6868696b40a34))
* **android:** bump media3 version from v1.1.1 to v1.2.0 ([#3362](https://github.com/nolemonnomelon/nn-react-native-video/issues/3362)) ([17dbf6e](https://github.com/nolemonnomelon/nn-react-native-video/commit/17dbf6e8264c5c6bed10ff23d96c2b7296a49651))
* **android:** cache ([#3514](https://github.com/nolemonnomelon/nn-react-native-video/issues/3514)) ([ecc946d](https://github.com/nolemonnomelon/nn-react-native-video/commit/ecc946d1c1f9870c3f0a40fa426fa088017bd7cd))
* **android:** change default user agent value ([#3813](https://github.com/nolemonnomelon/nn-react-native-video/issues/3813)) ([089dc7e](https://github.com/nolemonnomelon/nn-react-native-video/commit/089dc7e03251983ed3e1581519ffe4b3020ff5f8))
* **android:** implement asset folder playback ([#3733](https://github.com/nolemonnomelon/nn-react-native-video/issues/3733)) ([e05da4e](https://github.com/nolemonnomelon/nn-react-native-video/commit/e05da4e9fe82b63cb1cebf70f6d11930b01124e0))
* **android:** make buffering strategy dynamic ([#3756](https://github.com/nolemonnomelon/nn-react-native-video/issues/3756)) ([e420418](https://github.com/nolemonnomelon/nn-react-native-video/commit/e420418e8f74894c443bd232e99f9b860e1d0b93))
* **android:** replace deprecated ExoPlayer2 with AndroidX media3 ([#3337](https://github.com/nolemonnomelon/nn-react-native-video/issues/3337)) ([f2e80e9](https://github.com/nolemonnomelon/nn-react-native-video/commit/f2e80e9f2d1acc97080d48913802639dd2f38346))
* **android:** update `isCodecSupported` to return enum ([812e9dc](https://github.com/nolemonnomelon/nn-react-native-video/commit/812e9dc84fd8bed2ab8e46883fc0366c9d6ed8c9))
* changed folder name to FabricExample ([0cd28cf](https://github.com/nolemonnomelon/nn-react-native-video/commit/0cd28cfdf16610860ee1d2371ec04f955e628754))
* implement onAudioTracks and onTextTracks on ios ([#3503](https://github.com/nolemonnomelon/nn-react-native-video/issues/3503)) ([6a49cba](https://github.com/nolemonnomelon/nn-react-native-video/commit/6a49cba273fa0a47e106f4abb8caeb4ab6dbe4c8))
* implement opacity to control visibility of subtitles ([#3583](https://github.com/nolemonnomelon/nn-react-native-video/issues/3583)) ([f4cce2e](https://github.com/nolemonnomelon/nn-react-native-video/commit/f4cce2ecdba0668c3ecf74d2fd7956df4dd8489d))
* implement startPosition ([#3355](https://github.com/nolemonnomelon/nn-react-native-video/issues/3355)) ([2648502](https://github.com/nolemonnomelon/nn-react-native-video/commit/2648502b364c2802f5a2a7302c31200905c0a807))
* **ios:** Add ios support for accessing WebVTT Subtitle Content  ([#3541](https://github.com/nolemonnomelon/nn-react-native-video/issues/3541)) ([253ffb5](https://github.com/nolemonnomelon/nn-react-native-video/commit/253ffb595633a4b18221339278f73c8416225f56))
* **ios:** add onBandwidthUpdate event ([#3331](https://github.com/nolemonnomelon/nn-react-native-video/issues/3331)) ([9054db3](https://github.com/nolemonnomelon/nn-react-native-video/commit/9054db35d7d5e4e6d54739fc9349576c03522d7c))
* **ios:** add playback functions to ref ([85c9e8f](https://github.com/nolemonnomelon/nn-react-native-video/commit/85c9e8f99083a0909d4e66890fea4183a3ea4871))
* **ios:** implement onPlaybackStateChanged callback ([#3307](https://github.com/nolemonnomelon/nn-react-native-video/issues/3307)) ([9373493](https://github.com/nolemonnomelon/nn-react-native-video/commit/9373493d6a447bfe059479c99cef2c11a849c8af))
* **ios:** migrate from deprecated methods ([#3444](https://github.com/nolemonnomelon/nn-react-native-video/issues/3444)) ([5aaa53d](https://github.com/nolemonnomelon/nn-react-native-video/commit/5aaa53d8b80f6bac1d48acb863bd449fb3c15b41))
* **ios:** update the way to get `keyWindow` ([#3448](https://github.com/nolemonnomelon/nn-react-native-video/issues/3448)) ([f35727f](https://github.com/nolemonnomelon/nn-react-native-video/commit/f35727f30e290bff0ac28a57103e617cd8bc97ac))
* **ios:** update timed metadata handler ([#3449](https://github.com/nolemonnomelon/nn-react-native-video/issues/3449)) ([481cc71](https://github.com/nolemonnomelon/nn-react-native-video/commit/481cc71eda7c7b741e59c51e9b9b34849e1c1dc0))
* move docs to github pages ([#3296](https://github.com/nolemonnomelon/nn-react-native-video/issues/3296)) ([85e30f0](https://github.com/nolemonnomelon/nn-react-native-video/commit/85e30f0335788a4ee6e6b3c362a3857600ed5f19))
* move require (local files) to `source.uri` ([#3535](https://github.com/nolemonnomelon/nn-react-native-video/issues/3535)) ([41ac781](https://github.com/nolemonnomelon/nn-react-native-video/commit/41ac7814121fc70a123fa4585dc9b1bd96e9629f))
* refactor resize prop handler ([#3286](https://github.com/nolemonnomelon/nn-react-native-video/issues/3286)) ([7fd7b3f](https://github.com/nolemonnomelon/nn-react-native-video/commit/7fd7b3ff3222aa655958440a5d9565094e3954cc))
* renamed with react-native-rename ([805ccb9](https://github.com/nolemonnomelon/nn-react-native-video/commit/805ccb9f47b76b2f5f14e9eee1b751998f6cd907))
* RN 0.73 support ([7e5bc48](https://github.com/nolemonnomelon/nn-react-native-video/commit/7e5bc488c7b658df5e4d5191c577383dadb2ad33))
* **sample:** add an option to make controls testable in basic sample ([568e180](https://github.com/nolemonnomelon/nn-react-native-video/commit/568e1806a2f5f585cba2a3350b478ebb16685a04))
* **sample:** merge ios and android samples ([#3015](https://github.com/nolemonnomelon/nn-react-native-video/issues/3015)) ([1f01376](https://github.com/nolemonnomelon/nn-react-native-video/commit/1f0137608a541118dcf0b419c74b4fdf4f75f008))
* setup pod-install script with fabric enabled on Podfile ([d81d59d](https://github.com/nolemonnomelon/nn-react-native-video/commit/d81d59d00f4760f4ddc536967720d1980f72046f))
* **tvos:** add custom image metadata option for tvos and add missing types for custom metadata properties ([#3280](https://github.com/nolemonnomelon/nn-react-native-video/issues/3280)) ([a855284](https://github.com/nolemonnomelon/nn-react-native-video/commit/a855284d8d9465c45950fc895224a2ae8673a0e3))
* upgrade exoplayer to v2.17.1 ([#2498](https://github.com/nolemonnomelon/nn-react-native-video/issues/2498)) ([daf5e59](https://github.com/nolemonnomelon/nn-react-native-video/commit/daf5e595eced2b2f6580e8d8a6205f14facdec46))
* **Windows:** Adds Windows support to react-native-video ([8cc1dbd](https://github.com/nolemonnomelon/nn-react-native-video/commit/8cc1dbda4fcb51e068fb2d3a5425048be0617402))


### Performance Improvements

* ensure we do not provide callback to native if no callback provided from app ([#3735](https://github.com/nolemonnomelon/nn-react-native-video/issues/3735)) ([c59d00a](https://github.com/nolemonnomelon/nn-react-native-video/commit/c59d00a0f0a0b63b6bbe931f1a9b4fef03667cb2))
* **ios:** add early returns ([#3741](https://github.com/nolemonnomelon/nn-react-native-video/issues/3741)) ([1d235a1](https://github.com/nolemonnomelon/nn-react-native-video/commit/1d235a1fea948b7b37ef20e75d953fcbd8c550c6))


### Reverts

* Revert "fix(android): video flickering add playback start (#3746)" (#3748) ([d25629b](https://github.com/nolemonnomelon/nn-react-native-video/commit/d25629bb62cb9a7772ec2704f678e0fdf4927d12)), closes [#3746](https://github.com/nolemonnomelon/nn-react-native-video/issues/3746) [#3748](https://github.com/nolemonnomelon/nn-react-native-video/issues/3748)
* Revert "fix: remove pausePlayback when audio focus loss event (#3496)" (#3504) ([aec7db6](https://github.com/nolemonnomelon/nn-react-native-video/commit/aec7db63901c42dd7a591b030bfc69daa8860341)), closes [#3496](https://github.com/nolemonnomelon/nn-react-native-video/issues/3496) [#3504](https://github.com/nolemonnomelon/nn-react-native-video/issues/3504)
* Revert "chore: update basic example" ([106257a](https://github.com/nolemonnomelon/nn-react-native-video/commit/106257aa80a047f87d9ac31d241089594f8dd53d)), closes [#3015](https://github.com/nolemonnomelon/nn-react-native-video/issues/3015)
* Revert "type _eventDispatcher as RCTEventDispatcherProtocol" ([1d4665f](https://github.com/nolemonnomelon/nn-react-native-video/commit/1d4665f9e8e163e8bfd2e9f46c9afda4ab3f4597))
* Revert "[ios] Adaptive fullscreen in landscape by device orientation (#1862)" (#2043) ([2dd5025](https://github.com/nolemonnomelon/nn-react-native-video/commit/2dd5025190c43f46ee937faee0c4e7127448b444)), closes [#1862](https://github.com/nolemonnomelon/nn-react-native-video/issues/1862) [#2043](https://github.com/nolemonnomelon/nn-react-native-video/issues/2043)


### BREAKING CHANGES

* **android:** move backBufferDurationMs from root props to bufferConfig

## [6.1.2](https://github.com/TheWidlarzGroup/react-native-video/compare/v6.1.1...v6.1.2) (2024-05-23)


### Bug Fixes

* **android:** revert previous fix not compatible with old java version ([#3828](https://github.com/TheWidlarzGroup/react-native-video/issues/3828)) ([69bde44](https://github.com/TheWidlarzGroup/react-native-video/commit/69bde447b825507533627c7b7d931e5a5d19ef75))

# [6.1.1](https://github.com/TheWidlarzGroup/react-native-video/compare/v6.1.0...v6.1.1) (2024-05-22)

### Bug Fixes
* **iOS:** sometimes aspect ratio is invalid ([#3821](https://github.com/TheWidlarzGroup/react-native-video/issues/3821)) ([dac0985](https://github.com/TheWidlarzGroup/react-native-video/commit/dac09854303335d8e37b633c37bca399499d1999))

### Features
* **android:** change default user agent value ([#3813](https://github.com/TheWidlarzGroup/react-native-video/issues/3813)) ([089dc7e](https://github.com/TheWidlarzGroup/react-native-video/commit/089dc7e03251983ed3e1581519ffe4b3020ff5f8))


# [6.1.0](https://github.com/TheWidlarzGroup/react-native-video/compare/v6.0.0...v6.1.0) (2024-05-22)


### Bug Fixes

* **android:** avoid blinking on video track change ([#3782](https://github.com/TheWidlarzGroup/react-native-video/issues/3782)) ([7b1e129](https://github.com/TheWidlarzGroup/react-native-video/commit/7b1e1293f67c0e25e0763d08d830fcf192bb713c))
* **android:** implement live configuration management ([#3792](https://github.com/TheWidlarzGroup/react-native-video/issues/3792)) ([e16730d](https://github.com/TheWidlarzGroup/react-native-video/commit/e16730de11d50b8a85cd09fa2b102fdbf777d8ad))
* **android:** implement seek backward in notification service ([#3808](https://github.com/TheWidlarzGroup/react-native-video/issues/3808)) ([94b3da3](https://github.com/TheWidlarzGroup/react-native-video/commit/94b3da3477af3d82e4b16e6c93beb5c92ccee59b))
* **android:** playback doesn't work with 0 startPositionMs ([#3784](https://github.com/TheWidlarzGroup/react-native-video/issues/3784)) ([66e0ba5](https://github.com/TheWidlarzGroup/react-native-video/commit/66e0ba579b84d745b4ca1b076d41d8eb880ef616))
* **android:** random android crash ([#3777](https://github.com/TheWidlarzGroup/react-native-video/issues/3777)) ([d4c9be2](https://github.com/TheWidlarzGroup/react-native-video/commit/d4c9be2ba09dd410f0d878ce3f6a1cca987f6713))
* **android:** remove remaining ad view when zapping ([#3786](https://github.com/TheWidlarzGroup/react-native-video/issues/3786)) ([324b461](https://github.com/TheWidlarzGroup/react-native-video/commit/324b46152703d813945778f55d87310d4e0b03cf))
* **android:** source metadata compare function ([#3775](https://github.com/TheWidlarzGroup/react-native-video/issues/3775)) ([6455380](https://github.com/TheWidlarzGroup/react-native-video/commit/6455380f9e15099b975dce9beaf9b9af8298f998))
* **tvos:** fix tvOS build and sample ([#3785](https://github.com/TheWidlarzGroup/react-native-video/issues/3785)) ([cd42dd7](https://github.com/TheWidlarzGroup/react-native-video/commit/cd42dd78c96e20da377c9b05c321218f1411ba97))


### Features

* add setVolume function to component's ref ([#3794](https://github.com/TheWidlarzGroup/react-native-video/issues/3794)) ([3cd7ab6](https://github.com/TheWidlarzGroup/react-native-video/commit/3cd7ab60b27e8820607bd83a5681bc7ba7e6c52e))
* **android:** add possibility to hide seekBar ([#3789](https://github.com/TheWidlarzGroup/react-native-video/issues/3789)) ([95e6140](https://github.com/TheWidlarzGroup/react-native-video/commit/95e6140eead56efab83871e29b57d30f4f11a77a))

# [6.0.0](https://github.com/TheWidlarzGroup/react-native-video/compare/v6.0.0-rc.2...v6.0.0) (2024-05-14)


### Bug Fixes

* **android:** poster hidding ([#3768](https://github.com/TheWidlarzGroup/react-native-video/issues/3768)) ([98b4a75](https://github.com/TheWidlarzGroup/react-native-video/commit/98b4a75a90c6bc97cde267ea1c6a4a68d0bfdf45))
* **android:** video tracks crash and clean ([#3767](https://github.com/TheWidlarzGroup/react-native-video/issues/3767)) ([219496f](https://github.com/TheWidlarzGroup/react-native-video/commit/219496ff3abf6d7362ae01fb66c0bf28dfb00510))

# [6.0.0-rc.2](https://github.com/TheWidlarzGroup/react-native-video/compare/v6.0.0-rc.1...v6.0.0-rc.2) (2024-05-13)


### Bug Fixes

* **avoid:** avoid early return in setSrc ([#3759](https://github.com/TheWidlarzGroup/react-native-video/issues/3759)) ([2e623ca](https://github.com/TheWidlarzGroup/react-native-video/commit/2e623ca0fb074e64a6125994effb8723f5c4ce59))
* **ios:** call `onLoadStart` earlier ([#3750](https://github.com/TheWidlarzGroup/react-native-video/issues/3750)) ([b3f08f6](https://github.com/TheWidlarzGroup/react-native-video/commit/b3f08f6c990f4670311e6d918aea191e72673057))
* **js:** fix onPlaybackStateChanged callback ([#3753](https://github.com/TheWidlarzGroup/react-native-video/issues/3753)) ([f87a793](https://github.com/TheWidlarzGroup/react-native-video/commit/f87a7938c6941c69915477fcf5f08c54a2635597))
* **ts:** add missing type ([#3757](https://github.com/TheWidlarzGroup/react-native-video/issues/3757)) ([2d94844](https://github.com/TheWidlarzGroup/react-native-video/commit/2d9484499cfb58d86b0aa82872d494a03fe67bba))


### Features

* **android:** make buffering strategy dynamic ([#3756](https://github.com/TheWidlarzGroup/react-native-video/issues/3756)) ([e420418](https://github.com/TheWidlarzGroup/react-native-video/commit/e420418e8f74894c443bd232e99f9b860e1d0b93))


### Reverts

* Revert "fix(android): video flickering add playback start (#3746)" (#3748) ([d25629b](https://github.com/TheWidlarzGroup/react-native-video/commit/d25629bb62cb9a7772ec2704f678e0fdf4927d12)), closes [#3746](https://github.com/TheWidlarzGroup/react-native-video/issues/3746) [#3748](https://github.com/TheWidlarzGroup/react-native-video/issues/3748)

# [6.0.0-rc.1](https://github.com/TheWidlarzGroup/react-native-video/compare/v6.0.0-rc.0...v6.0.0-rc.1) (2024-05-08)


### Bug Fixes

* **android:** prevent changing video track when video load ([#3683](https://github.com/TheWidlarzGroup/react-native-video/issues/3683)) ([6f61d7f](https://github.com/TheWidlarzGroup/react-native-video/commit/6f61d7f6e6969d05e4cee9bdb2e4cbc80d356e7f))
* **android:** video flickering add playback start ([#3746](https://github.com/TheWidlarzGroup/react-native-video/issues/3746)) ([b1cd52b](https://github.com/TheWidlarzGroup/react-native-video/commit/b1cd52bc58b3dfd02dab4784ea423ebddae874c4))
* avoid crash when setting index to 0 to tracks selection ([#3721](https://github.com/TheWidlarzGroup/react-native-video/issues/3721)) ([518a9a9](https://github.com/TheWidlarzGroup/react-native-video/commit/518a9a93e06686ba707427078a1770dc3d803b2b))
* **ios:** destroy adsManager when player detach from super view ([#3716](https://github.com/TheWidlarzGroup/react-native-video/issues/3716)) ([#3722](https://github.com/TheWidlarzGroup/react-native-video/issues/3722)) ([e96c173](https://github.com/TheWidlarzGroup/react-native-video/commit/e96c17321f1347818c1f5a38628d65b5b4bd5e7b))
* **ios:** ensure duration available when playing live ([#3710](https://github.com/TheWidlarzGroup/react-native-video/issues/3710)) ([d56b251](https://github.com/TheWidlarzGroup/react-native-video/commit/d56b251aef6d4ca1708c7bbada15016efbf12caf))
* **ios:** ensure orientation is correct on iOS ([#3719](https://github.com/TheWidlarzGroup/react-native-video/issues/3719)) ([1a8295c](https://github.com/TheWidlarzGroup/react-native-video/commit/1a8295c8bf30d53135d723fc9aface1a812be78a))
* **ios:** fix text track selection by index ([#3728](https://github.com/TheWidlarzGroup/react-native-video/issues/3728)) ([51e22ab](https://github.com/TheWidlarzGroup/react-native-video/commit/51e22abfe35978ee3fd1a7b3dc6f6c769d1b24bc))


### Features

* add notification controls ([#3723](https://github.com/TheWidlarzGroup/react-native-video/issues/3723)) ([8ad4be4](https://github.com/TheWidlarzGroup/react-native-video/commit/8ad4be459b935e30077e38cce696875ea9d6b21f))
* **android:** cache ([#3514](https://github.com/TheWidlarzGroup/react-native-video/issues/3514)) ([ecc946d](https://github.com/TheWidlarzGroup/react-native-video/commit/ecc946d1c1f9870c3f0a40fa426fa088017bd7cd))
* **android:** implement asset folder playback ([#3733](https://github.com/TheWidlarzGroup/react-native-video/issues/3733)) ([e05da4e](https://github.com/TheWidlarzGroup/react-native-video/commit/e05da4e9fe82b63cb1cebf70f6d11930b01124e0))


### Performance Improvements

* ensure we do not provide callback to native if no callback provided from app ([#3735](https://github.com/TheWidlarzGroup/react-native-video/issues/3735)) ([c59d00a](https://github.com/TheWidlarzGroup/react-native-video/commit/c59d00a0f0a0b63b6bbe931f1a9b4fef03667cb2))
* **ios:** add early returns ([#3741](https://github.com/TheWidlarzGroup/react-native-video/issues/3741)) ([1d235a1](https://github.com/TheWidlarzGroup/react-native-video/commit/1d235a1fea948b7b37ef20e75d953fcbd8c550c6))

# [6.0.0-rc.0](https://github.com/react-native-video/react-native-video/compare/v6.0.0-beta.8...v6.0.0-rc.0) (2024-04-22)


### Bug Fixes

* **android:** catch errors in `performOnPlayerView` ([#3685](https://github.com/react-native-video/react-native-video/issues/3685)) ([3e35326](https://github.com/react-native-video/react-native-video/commit/3e3532691ad42a53b9136fd52eb7f9a578e21b91))
* **android:** fixed bug where video would not be visible after remount and change of drm source ([#3668](https://github.com/react-native-video/react-native-video/issues/3668)) ([1af12f9](https://github.com/react-native-video/react-native-video/commit/1af12f9dfb107c58a1896ee3181cb2c1a4fe300f))
* **android:** seek callback with controls ([#3694](https://github.com/react-native-video/react-native-video/issues/3694)) ([c730306](https://github.com/react-native-video/react-native-video/commit/c730306e3a408be753febf6e5a6e9c2984a3bbb5))
* **android:** set title for external subtitles ([#3676](https://github.com/react-native-video/react-native-video/issues/3676)) ([336b9f0](https://github.com/react-native-video/react-native-video/commit/336b9f022065b881eb31038ea1adba9dc54b2a08))
* ensure poster works as expected and add it to the sample ([#3643](https://github.com/react-native-video/react-native-video/issues/3643)) ([d694139](https://github.com/react-native-video/react-native-video/commit/d6941392e071f2bd50fbe832dde203b7f18da769))
* ensure tracks are available in sample ([#3660](https://github.com/react-native-video/react-native-video/issues/3660)) ([4c7719a](https://github.com/react-native-video/react-native-video/commit/4c7719a3f537509426c366d2176895661933c63c))
* **ios:** add workaround for `TouchableWithoutFeedback` ([#3688](https://github.com/react-native-video/react-native-video/issues/3688)) ([b5ccc48](https://github.com/react-native-video/react-native-video/commit/b5ccc48476d958f6b70d8a163a8d1209d1c3c302))
* **ios:** apply PictureInPicture state on start ([#3655](https://github.com/react-native-video/react-native-video/issues/3655)) ([07f71c2](https://github.com/react-native-video/react-native-video/commit/07f71c2fc446b43aa9565659983f7acb36d95f0c))
* **ios:** call PictureInPicture callbacks with native controls ([#3603](https://github.com/react-native-video/react-native-video/issues/3603)) ([051e884](https://github.com/react-native-video/react-native-video/commit/051e884c8f34755c887b66d8715a6ee38efc5f77)), closes [#3602](https://github.com/react-native-video/react-native-video/issues/3602) [#3602](https://github.com/react-native-video/react-native-video/issues/3602)
* **ios:** do not save pause state before seeking ([#3650](https://github.com/react-native-video/react-native-video/issues/3650)) ([e992243](https://github.com/react-native-video/react-native-video/commit/e992243305af0915442c3400f6ef105c4d5cd44c))
* **ios:** fix sideloading external subtitles ([#3690](https://github.com/react-native-video/react-native-video/issues/3690)) ([efa1c52](https://github.com/react-native-video/react-native-video/commit/efa1c52491cb069f6f4ba92ba56cf38624fecfde))
* **ios:** update onPlaybackStateChanged implementation ([#3687](https://github.com/react-native-video/react-native-video/issues/3687)) ([042e13c](https://github.com/react-native-video/react-native-video/commit/042e13c1dc3f88a42cd9293b064f9cebacecc831))
* **ios:** workaround for rate change ([#3657](https://github.com/react-native-video/react-native-video/issues/3657)) ([e26afac](https://github.com/react-native-video/react-native-video/commit/e26afac403e0b3675138f18569b08b4c9000cd81))
* prevents crash from occurring when using the selected video track with resolution type ([#3664](https://github.com/react-native-video/react-native-video/issues/3664)) ([e82f9dc](https://github.com/react-native-video/react-native-video/commit/e82f9dc24b6a4a09786f5425153b53494d72b05d))
* **ts:** onPlaybackRateChangeData was not correctly typed ([#3651](https://github.com/react-native-video/react-native-video/issues/3651)) ([2a858df](https://github.com/react-native-video/react-native-video/commit/2a858df8bce4dd6c529853bba5bac85f798c662e))


### Features

* **android:** allow to disable selected functionalities  ([#3681](https://github.com/react-native-video/react-native-video/issues/3681)) ([64e3191](https://github.com/react-native-video/react-native-video/commit/64e3191f73c828067094031a55e6868696b40a34))

# [6.0.0-beta.8](https://github.com/react-native-video/react-native-video/compare/v6.0.0-beta.7...v6.0.0-beta.8) (2024-04-03)


### Bug Fixes

* **android:** update ui manager getter ([#3634](https://github.com/react-native-video/react-native-video/issues/3634)) ([e87c14a](https://github.com/react-native-video/react-native-video/commit/e87c14a4375d47a03447716b1920608855df5d8d))
* fix codegen types ([#3636](https://github.com/react-native-video/react-native-video/issues/3636)) ([9b66e7f](https://github.com/react-native-video/react-native-video/commit/9b66e7fdce0393c4e2154a23b407de6c46dc9490))

# [6.0.0-beta.7](https://github.com/react-native-video/react-native-video/compare/v6.0.0-beta.6...v6.0.0-beta.7) (2024-03-30)


### Bug Fixes

* **android:** ensure rate is never set to 0 ([#3593](https://github.com/react-native-video/react-native-video/issues/3593)) ([3d7444a](https://github.com/react-native-video/react-native-video/commit/3d7444ab25c365b36e0e8d2672b74f474bba12eb))
* **android:** improve and backBufferDurationMs. mainly let exoplayer manage the prop ([#3619](https://github.com/react-native-video/react-native-video/issues/3619)) ([f10511d](https://github.com/react-native-video/react-native-video/commit/f10511d9534257a8fc9a4a47978d9c844428f1f7))
* **android:** keep screen on on fullscreen ([#3563](https://github.com/react-native-video/react-native-video/issues/3563)) ([bfb76e6](https://github.com/react-native-video/react-native-video/commit/bfb76e6d15f88a7dc50c63958486375e142a26bd))
* **android:** track selection parameter has change in last release. ([#3594](https://github.com/react-native-video/react-native-video/issues/3594)) ([d5c8b51](https://github.com/react-native-video/react-native-video/commit/d5c8b514a1af23fa473f32b434612feac46fd321))
* fix getLicense function's type definition ([#3606](https://github.com/react-native-video/react-native-video/issues/3606)) ([89ae843](https://github.com/react-native-video/react-native-video/commit/89ae8438fa1d90700a462b117aa9af42780c6268))
* inject onGetLicense prop properly for detect user defined or not ([#3608](https://github.com/react-native-video/react-native-video/issues/3608)) ([24c1aab](https://github.com/react-native-video/react-native-video/commit/24c1aab3f5ab6d2d753199ea16e01c993cc3ef7d))
* **iOS:** fix iOS DRM header parser ([#3609](https://github.com/react-native-video/react-native-video/issues/3609)) ([c9a75f3](https://github.com/react-native-video/react-native-video/commit/c9a75f3cde82f55e612b9e2c30ca06db3093b283))
* **ios:** fix PiP callback ([#3601](https://github.com/react-native-video/react-native-video/issues/3601)) ([bb9e7eb](https://github.com/react-native-video/react-native-video/commit/bb9e7eb5a5d68de1d8945be2f3fa089ca6ce2465))
* **ios:** fix regression when playing source starting with ph:// ([#3630](https://github.com/react-native-video/react-native-video/issues/3630)) ([75d3707](https://github.com/react-native-video/react-native-video/commit/75d370742b95ddf0eb114ef48620e188e6fdfad1))
* **ios:** fix startPosition, cropStart and cropEnd to handle float values correctly ([#3589](https://github.com/react-native-video/react-native-video/issues/3589)) ([36bd2e2](https://github.com/react-native-video/react-native-video/commit/36bd2e2d71dc6879d74b154ecc39ea7b27f4b565))
* **iOS:** throw when content id defined with empty string ([#3612](https://github.com/react-native-video/react-native-video/issues/3612)) ([0983580](https://github.com/react-native-video/react-native-video/commit/098358076ddaba387284c1757a80bfcc5d82191f))
* remove `setNativeProps` usage ([#3605](https://github.com/react-native-video/react-native-video/issues/3605)) ([0312afc](https://github.com/react-native-video/react-native-video/commit/0312afc8ea27f8c82ef7ba9fecbde23174e68671))


### BREAKING CHANGES

* **android:** move backBufferDurationMs from root props to bufferConfig

# [6.0.0-beta.6](https://github.com/react-native-video/react-native-video/compare/v6.0.0-beta.5...v6.0.0-beta.6) (2024-03-18)


### Bug Fixes

* add missing node_modules paths to metro.config.js of basic example app ([#3555](https://github.com/react-native-video/react-native-video/issues/3555)) ([d505de5](https://github.com/react-native-video/react-native-video/commit/d505de5910a22ab9a0d7429e6b88a81cd2594b9c))
* add missing shutterColor type ([#3561](https://github.com/react-native-video/react-native-video/issues/3561)) ([ba00881](https://github.com/react-native-video/react-native-video/commit/ba00881ddcd53c2f5a4e1fc6e30cb5eb7ef674a3))
* **android:** check disableFocus when state is ready ([#3494](https://github.com/react-native-video/react-native-video/issues/3494)) ([366c841](https://github.com/react-native-video/react-native-video/commit/366c841c0b960fd461ae7dcfdcb76a928fadf2b8))
* **android:** enableDecoderFallback to decrease DECODER_ERROR issue ([#3416](https://github.com/react-native-video/react-native-video/issues/3416)) ([eaa72c6](https://github.com/react-native-video/react-native-video/commit/eaa72c66659b9e2a22af9ff9d43013521f6a66e3))
* **android:** onSeek called instantly ([#3530](https://github.com/react-native-video/react-native-video/issues/3530)) ([af6aea8](https://github.com/react-native-video/react-native-video/commit/af6aea8934e19467e1ed8e21808b2dbddb6f6356))
* **android:** suppress lint `PrivateResource` ([#3531](https://github.com/react-native-video/react-native-video/issues/3531)) ([38e3625](https://github.com/react-native-video/react-native-video/commit/38e3625541753340e912e474b753e0f4fac4e9c1))
* **docs/ci:** add typescript ([#3572](https://github.com/react-native-video/react-native-video/issues/3572)) ([0f31271](https://github.com/react-native-video/react-native-video/commit/0f31271dcf2bfe2f4429e22040660025be8a6a3c))
* **docs:** fix build ([#3571](https://github.com/react-native-video/react-native-video/issues/3571)) ([4fc7d27](https://github.com/react-native-video/react-native-video/commit/4fc7d2788b4d01c581a31cc3ac733c3948b65a3a))
* **ios:** add text tracks only if we successfully insertTimeRage ([#3557](https://github.com/react-native-video/react-native-video/issues/3557)) ([b73baad](https://github.com/react-native-video/react-native-video/commit/b73baad2c2c0c6ea701d865eee32d4e94ae58178))
* **ios:** apply `cropStart` when in repeat mode ([#3525](https://github.com/react-native-video/react-native-video/issues/3525)) ([2c0e009](https://github.com/react-native-video/react-native-video/commit/2c0e00987685875f9603ae2084ae23b3c1aebce7))
* **ios:** current release volume change observer ([#3565](https://github.com/react-native-video/react-native-video/issues/3565)) ([16f3cdb](https://github.com/react-native-video/react-native-video/commit/16f3cdbd9a7864206feaeef29344c09792d66d56))
* **ios:** Do not crash when accessLog return nil ([#3549](https://github.com/react-native-video/react-native-video/issues/3549)) ([4d4b56c](https://github.com/react-native-video/react-native-video/commit/4d4b56c05dd3c09fce5ddc38f56b0391c357ac85))
* **ios:** don't crop video when in repeat mode ([#3575](https://github.com/react-native-video/react-native-video/issues/3575)) ([90b31af](https://github.com/react-native-video/react-native-video/commit/90b31af2c969b6d6d57877c71ef3a4830a76aedc))
* **ios:** ensure playback stopped in background ([#3587](https://github.com/react-native-video/react-native-video/issues/3587)) ([41c6785](https://github.com/react-native-video/react-native-video/commit/41c6785ee8c667ebe9c6c464223f6485473d94f8))
* **ios:** fix missing bridge in bridgeless mode ([#3570](https://github.com/react-native-video/react-native-video/issues/3570)) ([46c8c49](https://github.com/react-native-video/react-native-video/commit/46c8c498c474600a0b35ebaf744306aefa42905f))
* **ios:** fix tvOS build ([#3524](https://github.com/react-native-video/react-native-video/issues/3524)) ([9306d9a](https://github.com/react-native-video/react-native-video/commit/9306d9a15d281a60492f6d4166598a389a56f652))
* **ios:** split licenseUrl and loadedLicenseUrl ([#3578](https://github.com/react-native-video/react-native-video/issues/3578)) ([7c4d19f](https://github.com/react-native-video/react-native-video/commit/7c4d19fa72a35449dd11ec59278b2ea11ec629fc))


### Features

* **android:** add subtitle event ([#3566](https://github.com/react-native-video/react-native-video/issues/3566)) ([6184c10](https://github.com/react-native-video/react-native-video/commit/6184c10acc90defd63cd55af51458864dfe112d5))
* implement opacity to control visibility of subtitles ([#3583](https://github.com/react-native-video/react-native-video/issues/3583)) ([f4cce2e](https://github.com/react-native-video/react-native-video/commit/f4cce2ecdba0668c3ecf74d2fd7956df4dd8489d))
* **ios:** Add ios support for accessing WebVTT Subtitle Content  ([#3541](https://github.com/react-native-video/react-native-video/issues/3541)) ([253ffb5](https://github.com/react-native-video/react-native-video/commit/253ffb595633a4b18221339278f73c8416225f56))
* move require (local files) to `source.uri` ([#3535](https://github.com/react-native-video/react-native-video/issues/3535)) ([41ac781](https://github.com/react-native-video/react-native-video/commit/41ac7814121fc70a123fa4585dc9b1bd96e9629f))

# [6.0.0-beta.5](https://github.com/react-native-video/react-native-video/compare/v6.0.0-beta.4...v6.0.0-beta.5) (2024-02-02)


### Bug Fixes

* **android:** fix crash with interop layer ([#3509](https://github.com/react-native-video/react-native-video/issues/3509)) ([41e9bcb](https://github.com/react-native-video/react-native-video/commit/41e9bcb1ef28c1532863186c83423814fcaf2372))
* **android:** re-layout controls after fullscreen dismiss ([#3490](https://github.com/react-native-video/react-native-video/issues/3490)) ([135d97c](https://github.com/react-native-video/react-native-video/commit/135d97ce506bf1a0226042e0f29f4de5bcc10972))
* fix typo ([#3497](https://github.com/react-native-video/react-native-video/issues/3497)) ([336eb44](https://github.com/react-native-video/react-native-video/commit/336eb44dc6061dad9cdc3382eb05d0a0effbef64))
* **ios:** fix pip memory leak ([#3506](https://github.com/react-native-video/react-native-video/issues/3506)) ([53068dd](https://github.com/react-native-video/react-native-video/commit/53068ddd41218bb615cd129eba2c36d6347ccf25))
* remove lifecycle listener after component unmount ([#3489](https://github.com/react-native-video/react-native-video/issues/3489)) ([3858a15](https://github.com/react-native-video/react-native-video/commit/3858a15b4268ae54d5b97c036d86b05aaf31bcf9)), closes [#3488](https://github.com/react-native-video/react-native-video/issues/3488)
* remove pausePlayback when audio focus loss event ([#3496](https://github.com/react-native-video/react-native-video/issues/3496)) ([b1ab0f2](https://github.com/react-native-video/react-native-video/commit/b1ab0f24a3efbcc3be49005060f50b34a117664e))


### Features

* implement onAudioTracks and onTextTracks on ios ([#3503](https://github.com/react-native-video/react-native-video/issues/3503)) ([6a49cba](https://github.com/react-native-video/react-native-video/commit/6a49cba273fa0a47e106f4abb8caeb4ab6dbe4c8))


### Reverts

* Revert "fix: remove pausePlayback when audio focus loss event (#3496)" (#3504) ([aec7db6](https://github.com/react-native-video/react-native-video/commit/aec7db63901c42dd7a591b030bfc69daa8860341)), closes [#3496](https://github.com/react-native-video/react-native-video/issues/3496) [#3504](https://github.com/react-native-video/react-native-video/issues/3504)

# [6.0.0-beta.4](https://github.com/react-native-video/react-native-video/compare/v6.0.0-beta.3...v6.0.0-beta.4) (2024-01-15)


### Bug Fixes
* add missing audioOutput prop (#3450) (f20d68b)
* **android**: support opacity properly (#3464) (11e5b75)
* **ios**: currentPlaybackTime in ms and not seconds (#3472) (3f63c16)
* **ios**: remove extra dismissFullscreenPlayer declaration (#3474) (045f5fa)

### Features
* add visionOS support (#3425) (cf3ebb7)
* **ios**: migrate from deprecated methods (#3444) (5aaa53d)
* **ios**: update the way to get keyWindow (#3448) (f35727f)
* **ios**: update timed metadata handler (#3449) (481cc71)

# [6.0.0-beta.3](https://github.com/react-native-video/react-native-video/compare/v6.0.0-beta.2...v6.0.0-beta.3) (2023-12-24)


### Bug Fixes

* **android:** default UA ([#3429](https://github.com/react-native-video/react-native-video/issues/3429)) ([dd7bb54](https://github.com/react-native-video/react-native-video/commit/dd7bb54720c06eca045d72e7557d6f472a793b6f))
* ensure save doesn't crash on android ([#3415](https://github.com/react-native-video/react-native-video/issues/3415)) ([22a2655](https://github.com/react-native-video/react-native-video/commit/22a2655dca4bb53074ce5a74cfeb7f9bb26b13a3))
* **ios:** revert ios url encoding as this breaks encoded urls ([#3440](https://github.com/react-native-video/react-native-video/issues/3440)) ([0723481](https://github.com/react-native-video/react-native-video/commit/0723481fee75890bc2fff967e3b5bc8946e481a3))
* **ReactVideoProps:** add accessibility & testID in typing ([#3434](https://github.com/react-native-video/react-native-video/issues/3434)) ([d986b7b](https://github.com/react-native-video/react-native-video/commit/d986b7bf57f8fe49cbf5f507efde4aeb28ee34f8))

# [6.0.0-beta.2](https://github.com/react-native-video/react-native-video/compare/v6.0.0-beta.1...v6.0.0-beta.2) (2023-12-08)


### Bug Fixes

* add allowsExternalPlayback missing on ReactVideoProps ([#3398](https://github.com/react-native-video/react-native-video/issues/3398)) ([72679a7](https://github.com/react-native-video/react-native-video/commit/72679a7d639b9c000e060af0dbab7c862c180b00))
* **android:** add explicitly dependancy to androidx.activity ([#3410](https://github.com/react-native-video/react-native-video/issues/3410)) ([908e30f](https://github.com/react-native-video/react-native-video/commit/908e30f9b8d950fa1423a10d4b08135b6cc4d43a))
* **android:** ensure adTagUrl can be reset ([#3408](https://github.com/react-native-video/react-native-video/issues/3408)) ([f9bcaac](https://github.com/react-native-video/react-native-video/commit/f9bcaac5158ea2d835dd3177b62ad0446eb30d67))
* revert drm type definition change ([#3409](https://github.com/react-native-video/react-native-video/issues/3409)) ([fbb5654](https://github.com/react-native-video/react-native-video/commit/fbb5654a8e075a2b33ae17bd322bb79b1f459d53))

# [6.0.0-beta.1](https://github.com/react-native-video/react-native-video/compare/v6.0.0-beta.0...v6.0.0-beta.1) (2023-12-02)


### Bug Fixes

* **android:** ads build and enable ads in android sample ([#3376](https://github.com/react-native-video/react-native-video/issues/3376)) ([fe89122](https://github.com/react-native-video/react-native-video/commit/fe89122524826093689118a4515802d83ca88679))
* **android:** fix leak caused by removing lifecycle listener too early ([#3380](https://github.com/react-native-video/react-native-video/issues/3380)) ([0c0f317](https://github.com/react-native-video/react-native-video/commit/0c0f3174cb37d3c664a345ea00fcbaafffcd4b10))
* **android:** revert media3 update, back to 1.1.1 ([#3369](https://github.com/react-native-video/react-native-video/issues/3369)) ([5beef38](https://github.com/react-native-video/react-native-video/commit/5beef383cba13d3ac471bfde27e4acfaa19adfec))
* **ios:** check for ios url query encoding ([#3384](https://github.com/react-native-video/react-native-video/issues/3384)) ([de4159f](https://github.com/react-native-video/react-native-video/commit/de4159f0c2825a58d88f3882215da4bf51fdbeb2))
* **ios:** fix pip(when player doesn't fill screen) ([#3363](https://github.com/react-native-video/react-native-video/issues/3363)) ([11f6201](https://github.com/react-native-video/react-native-video/commit/11f62013e33939ce3f78ec7cf40e4da464afa824))


### Features

* **ad:** add data to onReceiveAdEvent ([#3378](https://github.com/react-native-video/react-native-video/issues/3378)) ([d05231d](https://github.com/react-native-video/react-native-video/commit/d05231d76b87e2f65bc7648bfb81d01e4054b2de))
* add AdEvent enum to have an exhaustive list of all possible AdEvent values ([#3374](https://github.com/react-native-video/react-native-video/issues/3374)) ([b3744f9](https://github.com/react-native-video/react-native-video/commit/b3744f9b9f25b469fb8b0828e3762842bd5026de))
* add onAdError event listener ([#3381](https://github.com/react-native-video/react-native-video/issues/3381)) ([596c02d](https://github.com/react-native-video/react-native-video/commit/596c02d2b3b5175e1653844c39a47ecfd5e23163))
* **android:** bump media3 version from v1.1.1 to v1.2.0 ([#3362](https://github.com/react-native-video/react-native-video/issues/3362)) ([17dbf6e](https://github.com/react-native-video/react-native-video/commit/17dbf6e8264c5c6bed10ff23d96c2b7296a49651))
* implement startPosition ([#3355](https://github.com/react-native-video/react-native-video/issues/3355)) ([2648502](https://github.com/react-native-video/react-native-video/commit/2648502b364c2802f5a2a7302c31200905c0a807))

# [6.0.0-beta.1](https://github.com/react-native-video/react-native-video/compare/v6.0.0-beta.0...v6.0.0-beta.1) (WIP)
* **android:** fix leak caused by removing lifecycle listener too early ([#3380](https://github.com/react-native-video/react-native-video/pull/3380))

# [6.0.0-beta.0](https://github.com/react-native-video/react-native-video/compare/v6.0.0-alpha.11...v6.0.0-beta.0) (2023-11-18)


### Bug Fixes

* **example:** remove dependency loop ([#3353](https://github.com/react-native-video/react-native-video/issues/3353)) ([211c3c7](https://github.com/react-native-video/react-native-video/commit/211c3c7d08c8438bfca3350f0070cfec0ae5bc56))
* **ios:** change isPlaybackLikelyToKeepUp check ([#3357](https://github.com/react-native-video/react-native-video/issues/3357)) ([1ba93f9](https://github.com/react-native-video/react-native-video/commit/1ba93f9e9d33f653f0e01214f220e1e5eda819f5))
* **ios:** fix cache playerItemPrepareText type ([#3358](https://github.com/react-native-video/react-native-video/issues/3358)) ([0e23952](https://github.com/react-native-video/react-native-video/commit/0e23952cea5c71324a2f5eea0383c4db9e02504b))
* **ios:** fix external text tracks crashes with m3u8 files ([#3330](https://github.com/react-native-video/react-native-video/issues/3330)) ([782e7e0](https://github.com/react-native-video/react-native-video/commit/782e7e0df1386ef0aad3f00d73171d04d6cf725d))
* update onError definition to match implementation ([#3349](https://github.com/react-native-video/react-native-video/issues/3349)) ([fdbd6a6](https://github.com/react-native-video/react-native-video/commit/fdbd6a6ba8aef2da854ff7b0fbf25085ce6983e3))


### Features

* **android:** replace deprecated ExoPlayer2 with AndroidX media3 ([#3337](https://github.com/react-native-video/react-native-video/issues/3337)) ([f2e80e9](https://github.com/react-native-video/react-native-video/commit/f2e80e9f2d1acc97080d48913802639dd2f38346))

# [6.0.0-alpha.11](https://github.com/react-native-video/react-native-video/compare/v6.0.0-alpha.10...v6.0.0-alpha.11) (2023-11-15)


### Bug Fixes

* fix bad package release process ([#3347](https://github.com/react-native-video/react-native-video/issues/3347)) ([f961f95](https://github.com/react-native-video/react-native-video/commit/f961f952a483192ee3de1f7bae59419ec6ddc5b7))

# [6.0.0-alpha.10](https://github.com/react-native-video/react-native-video/compare/v6.0.0-alpha.9...v6.0.0-alpha.10) (2023-11-13)


### Bug Fixes

* fixes where Android's muted prop behavior differs from iOS ([#3339](https://github.com/react-native-video/react-native-video/issues/3339)) ([8fbdc28](https://github.com/react-native-video/react-native-video/commit/8fbdc28a73a0b3ffd3691ef0c8cf523c760ae288))
* **ios:** fix wrong fullscreen method definition ([#3338](https://github.com/react-native-video/react-native-video/issues/3338)) ([7f49b56](https://github.com/react-native-video/react-native-video/commit/7f49b560278262fb4276f931404c70672a6445c8))
* **ios:** player is frozen after re-focusing on the app ([#3326](https://github.com/react-native-video/react-native-video/issues/3326)) ([722ae34](https://github.com/react-native-video/react-native-video/commit/722ae3477a68aecb812b26d71ea22a17dda71f50))


### Features

* add `onVolumeChange` event ([#3322](https://github.com/react-native-video/react-native-video/issues/3322)) ([cdbc856](https://github.com/react-native-video/react-native-video/commit/cdbc85638789da0002cdadb13190963d4c1332c2))
* add release-it ([#3342](https://github.com/react-native-video/react-native-video/issues/3342)) ([da27089](https://github.com/react-native-video/react-native-video/commit/da270891fbce485bb132825a336638f2af98408d))
* **ios:** add onBandwidthUpdate event ([#3331](https://github.com/react-native-video/react-native-video/issues/3331)) ([9054db3](https://github.com/react-native-video/react-native-video/commit/9054db35d7d5e4e6d54739fc9349576c03522d7c))

## Changelog

## Next
- Android, iOS: add onVolumeChange event #3322
- iOS: Externally loaded text tracks not loading properly [#3461](https://github.com/react-native-video/react-native-video/pull/3461)

### Version 6.0.0-alpha.9
- All: add built-in typescript support [#3266](https://github.com/react-native-video/react-native-video/pull/3266)
- All: update documentation generation [#3296](https://github.com/react-native-video/react-native-video/pull/3296)
- **BREAKING CHANGE**❗️Android: update isCodecSupported to return enum [#3254](https://github.com/react-native-video/react-native-video/pull/3254)
- Android: use explicit not-exported flag for AudioBecomingNoisyReceiver [#3327](https://github.com/react-native-video/react-native-video/pull/3327)
- Android: remove kotlin-android-extensions [#3299](https://github.com/react-native-video/react-native-video/pull/3299)
- Android: ensure audio volume is changed in UI thread [3292](https://github.com/react-native-video/react-native-video/pull/3292)
- Android: multiple internal refactor and switch to kotlin
- Android: refactor log management and add an option to increase log verbosity [#3277](https://github.com/react-native-video/react-native-video/pull/3277)
- iOS: Fix audio session category when not using the audioOutput prop
- iOS: implement onPlaybackStateChanged callback [#3307](https://github.com/react-native-video/react-native-video/pull/3307)
- iOS: remove false calls at onPlaybackRateChange [#3306](https://github.com/react-native-video/react-native-video/pull/3306)
- iOS: audio does not work with headphones [#3284](https://github.com/react-native-video/react-native-video/pull/3284)
- iOS: Resuming video ad after closing the in-app browser on iOS [#3275](https://github.com/react-native-video/react-native-video/pull/3275)
- iOS, Android: expose playback functions to ref [#3245](https://github.com/react-native-video/react-native-video/pull/3245)
- tvOS: fix build: [#3276](https://github.com/react-native-video/react-native-video/pull/3276)
- Windows: fix build error from over-specified SDK version [#3246](https://github.com/react-native-video/react-native-video/pull/3246)
- Windows: fix `onError` not being raised [#3247](https://github.com/react-native-video/react-native-video/pull/3247)

### Version 6.0.0-alpha.8
- All: Playing audio over earpiece [#2887](https://github.com/react-native-video/react-native-video/issues/2887)
- All: Prepare for fabric [#3175](https://github.com/react-native-video/react-native-video/pull/3175) [#]()
- iOS: Fix Pip [#3221](https://github.com/react-native-video/react-native-video/pull/3221)
- iOS: Fix regression in presentFullscreenPlayer & dismissFullscreenPlayer [#3230](https://github.com/react-native-video/react-native-video/pull/3230)
- tvOS: Fix build [#3207](https://github.com/react-native-video/react-native-video/pull/3207)
- tvOS: Add sample [#3208](https://github.com/react-native-video/react-native-video/pull/3208)
- tvOS: Allow chapter customization [#3216](https://github.com/react-native-video/react-native-video/pull/3216)
- doc: Fix internal links [#3229](https://github.com/react-native-video/react-native-video/pull/3229)

### Version 6.0.0-alpha.7
- All: clean JS warnings (https://github.com/react-native-video/react-native-video/pull/3183)
- Android: Add shutterView color configurtion (https://github.com/react-native-video/react-native-video/pull/3179)
- Android: React native 0.73 support (https://github.com/react-native-video/react-native-video/pull/3163)
- Android: Fix memory leaks from AudioManager [#3123](https://github.com/react-native-video/react-native-video/pull/3123)
- Android: Fixed syntax error [#3182](https://github.com/react-native-video/react-native-video/issues/3182)
- iOS: Fix freeze at playback startup (https://github.com/react-native-video/react-native-video/pull/3173)
- iOS: Various safety checks (https://github.com/react-native-video/react-native-video/pull/3168)

### Version 6.0.0-alpha.6
- Feature: Video range support [#3030](https://github.com/react-native-video/react-native-video/pull/3030)
- iOS: remove undocumented `currentTime` property [#3064](https://github.com/react-native-video/react-native-video/pull/3064)
- iOS: make sure that the audio in ads is muted when the player is muted. [#3068](https://github.com/react-native-video/react-native-video/pull/3077)
- iOS: make IMA build optionnal

### Version 6.0.0-alpha.5

- iOS: ensure controls are not displayed when disabled by user [#3017](https://github.com/react-native-video/react-native-video/pull/3017)
- iOS: app crashes on call to presentFullScreenPlayer [#2808](https://github.com/react-native-video/react-native-video/pull/2971)
- Android: Fix publicated progress handler causing duplicated progress event [#2972](https://github.com/react-native-video/react-native-video/pull/2972)
- Android: Fix audio/Subtitle tracks selection [#2979](https://github.com/react-native-video/react-native-video/pull/2979)
- Android: add new events on tracks changed to be notified of audio/text/video Tracks update during playback [2806](https://github.com/react-native-video/react-native-video/pull/2806)
- Feature: Add VAST support for AVOD [#2923](https://github.com/react-native-video/react-native-video/pull/2923)
- Sample: Upgrade react-native version of basic sample [#2960](https://github.com/react-native-video/react-native-video/pull/2960)

### Version 6.0.0-alpha.4

- ensure src is always provided to native player even if it is invalid [#2857](https://github.com/react-native-video/react-native-video/pull/2857)
- Sample: Add react-native-video controls support [#2852](https://github.com/react-native-video/react-native-video/pull/2852)
- Android: Switch Google's maven repository to default `google()` [#2860](https://github.com/react-native-video/react-native-video/pull/2860)
- Android: Implement focusable prop so the video view can toggle whether it is focusable for non-touch devices [#2819](https://github.com/react-native-video/react-native-video/issues/2819)
- Android: fix linter warning [#2891] (https://github.com/react-native-video/react-native-video/pull/2891)
- Fix iOS RCTSwiftLog naming collision [#2868](https://github.com/react-native-video/react-native-video/issues/2868)
- Added "homepage" to package.json [#2882](https://github.com/react-native-video/react-native-video/pull/2882)
- Fix regression when fullscreen prop is used combined with controls [#2911](https://github.com/react-native-video/react-native-video/pull/2911)
- Fix: memory leak issue on iOS [#2907](https://github.com/react-native-video/react-native-video/pull/2907)
- Fix setting text tracks before player is initialized on iOS [#2935](https://github.com/react-native-video/react-native-video/pull/2935)

### Version 6.0.0-alpha.3

- Fix ios build [#2854](https://github.com/react-native-video/react-native-video/pull/2854)

### Version 6.0.0-alpha.2

- Upgrade ExoPlayer to 2.18.1 [#2846](https://github.com/react-native-video/react-native-video/pull/2846)
- Feature add new APIs to query supported features of device decoder (widevine level & codec capabilities) on android [#2740](https://github.com/react-native-video/react-native-video/pull/2740)
- Feature add support of subtitle styling on android [#2759](https://github.com/react-native-video/react-native-video/pull/2759)
- Fix Android #2690 ensure onEnd is not sent twice [#2690](https://github.com/react-native-video/react-native-video/issues/2690)
- Fix Exoplayer progress not reported when paused [#2664](https://github.com/react-native-video/react-native-video/pull/2664)
- Call playbackRateChange onPlay and onPause [#1493](https://github.com/react-native-video/react-native-video/pull/1493)
- Fix being unable to disable sideloaded texttracks in the AVPlayer [#2679](https://github.com/react-native-video/react-native-video/pull/2679)
- Fixed crash when iOS seek method called reject on the promise [#2743](https://github.com/react-native-video/react-native-video/pull/2743)
- Fix maxBitRate property being ignored on Android [#2670](https://github.com/react-native-video/react-native-video/pull/2670)
- Fix crash when the source is a cameraroll [#2639] (https://github.com/react-native-video/react-native-video/pull/2639)
- Fix IOS UI frame drop on loading video [#2848] (https://github.com/react-native-video/react-native-video/pull/2848)

### Version 6.0.0-alpha.1

- Remove Android MediaPlayer support [#2724](https://github.com/react-native-video/react-native-video/pull/2724)
  **WARNING**: when switching from older version to V6, you need to remove all refrerences of android-exoplayer. This android-exoplayer folder has been renamed to android. Exoplayer is now the only player implementation supported.

- Replace Image.propTypes with ImagePropTypes. [#2718](https://github.com/react-native-video/react-native-video/pull/2718)
- Fix iOS build caused by type mismatch [#2720](https://github.com/react-native-video/react-native-video/pull/2720)
- ERROR TypeError: undefined is not an object (evaluating '_reactNative.Image.propTypes.resizeMode') [#2714](https://github.com/react-native-video/react-native-video/pull/2714)
- Fix video endless loop when repeat set to false or not specified. [#2329](https://github.com/react-native-video/react-native-video/pull/2329)

### Version 6.0.0-alpha.0

- Support disabling buffering [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Fix AudioFocus bug that could cause the player to stop responding to play/pause in some instances. [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Fix player crashing when it is being cleared. [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Add support for customising back buffer duration and handle network errors gracefully to prevent releasing the player when network is lost. [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Allow player to be init before source is provided, and later update once a source is provided. [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Adds handling for providing a empty source in order to stop playback and clear out any existing content [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Add support for detecting if format is supported and exclude unsupported resolutions from auto quality selection and video track info in RN. [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Improve error handling [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Add support for L1 to L3 Widevine fallback if playback fails initially. [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Reduce buffer size based on available heap [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Force garbage collection when there is no available memory [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Improve memory usage [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Support disabling screen recording [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Improved error capturing [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Fix DRM init crashes [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Improve progress reporting [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Fix progress loss when network connection is regained [#2689](https://github.com/react-native-video/react-native-video/pull/2689)
- Add Google's maven repository to avoid build error [#2552](https://github.com/react-native-video/react-native-video/pull/2552)
- Fix iOS 15.4 HLS playback race condition [#2633](https://github.com/react-native-video/react-native-video/pull/2633)
- Fix app crash from NPE in Exoplayer error handler [#2575](https://github.com/react-native-video/react-native-video/pull/2575)
- Fix default closed captioning behavior for Android ExoPlayer [#2181](https://github.com/react-native-video/react-native-video/pull/2181)
- Disable pipController init if pictureInPicture is false [#2645](https://github.com/react-native-video/react-native-video/pull/2645)
- Make sure modifiers are applied before playing [#2395](https://github.com/react-native-video/react-native-video/pull/2395)
- Better support newer versions of RNW (64 and newer) [#2535](https://github.com/react-native-video/react-native-video/pull/2535)
- Fix nil string uri parameter error [#695](https://github.com/react-native-video/react-native-video/pull/695)
- (Breaking) Bump shaka-player to 3.3.2 [#2587](https://github.com/react-native-video/react-native-video/pull/2587)
- Improve basic player example on android [#2662](https://github.com/react-native-video/react-native-video/pull/2662)
- Ensure we always use `hideShutterView` before showing the `shutterView` on Android [#2609](https://github.com/react-native-video/react-native-video/pull/2609)
- Convert iOS implementation to Swift [#2527](https://github.com/react-native-video/react-native-video/pull/2527)
- Add iOS support for decoding offline sources [#2527](https://github.com/react-native-video/react-native-video/pull/2527)
- Update basic example applications (React Native 0.63.4) [#2527](https://github.com/react-native-video/react-native-video/pull/2527)
- Upgrade ExoPlayer to 2.17.1 [#2498](https://github.com/react-native-video/react-native-video/pull/2498)
- Fix volume reset issue in exoPlayer [#2371](https://github.com/react-native-video/react-native-video/pull/2371)
- Change WindowsTargetPlatformVersion to 10.0 [#2706](https://github.com/react-native-video/react-native-video/pull/2706)
- Fixed Android seeking bug [#2712](https://github.com/react-native-video/react-native-video/pull/2712)
- Fixed `onReadyForDisplay` not being called [#2721](https://github.com/react-native-video/react-native-video/pull/2721)
- Fix type of `_eventDispatcher` on iOS target to match `bridge.eventDispatcher()` [#2720](https://github.com/react-native-video/react-native-video/pull/2720)

### Version 5.2.0

- Fix for tvOS native audio menu language selector
- Update ExoPlayer to allow pre-init and content clear [#2412] (https://github.com/react-native-video/react-native-video/pull/2412)
- iOS rate is reset to 1.0 after play/pause [#2167] (https://github.com/react-native-video/react-native-video/pull/2167)
- Upgrade ExoPlayer to 2.13.2 [#2317] (https://github.com/react-native-video/react-native-video/pull/2317)
- Fix AudioFocus pausing video when attempting to play [#2311] (https://github.com/react-native-video/react-native-video/pull/2311)

### Version 5.1.0-alpha9

- Add ARM64 support for windows [#2137](https://github.com/react-native-community/react-native-video/pull/2137)
- Fix deprecated API bug for windows [#2119](https://github.com/react-native-video/react-native-video/pull/2119)
- Added `rate` property and autolinking support for windows [#2206](https://github.com/react-native-video/react-native-video/pull/2206)

### Version 5.1.0-alpha8

- Fixing ID3 Frame Error When Receiving EventMessage in TimedMetadata [#2116](https://github.com/react-native-community/react-native-video/pull/2116)

### Version 5.1.0-alpha7

- Basic support for DRM on iOS and Android [#1445](https://github.com/react-native-community/react-native-video/pull/1445)

### Version 5.1.0-alpha6

- Fix iOS bug which would break size of views when video is displayed with controls on a non full-screen React view. [#1931](https://github.com/react-native-community/react-native-video/pull/1931)
- Fix video dimensions being undefined when playing HLS in ios. [#1992](https://github.com/react-native-community/react-native-video/pull/1992)
- Add support for audio mix with other apps for iOS. [#1978](https://github.com/react-native-community/react-native-video/pull/1978)
- Properly implement pending seek for iOS. [#1994](https://github.com/react-native-community/react-native-video/pull/1994)
- Added `preferredForwardBufferDuration` (iOS) - the duration the player should buffer media from the network ahead of the playhead to guard against playback disruption. (#1944)
- Added `currentPlaybackTime` (Android ExoPlayer, iOS) - when playing an HLS live stream with a `EXT-X-PROGRAM-DATE-TIME` tag configured, then this property will contain the epoch value in msec. (#1944)
- Added `trackId` (Android ExoPlayer) - Configure an identifier for the video stream to link the playback context to the events emitted. (#1944)
- Added preventsDisplaySleepDuringVideoPlayback (#2019)
- Reverted the JS fullscreening for Android. [#2013](https://github.com/react-native-community/react-native-video/pull/2013)
- Set iOS request headers without needing to edit RCTVideo.m. [#2014](https://github.com/react-native-community/react-native-video/pull/2014)
- Fix exoplayer aspect ratio update on source changes [#2053](https://github.com/react-native-community/react-native-video/pull/2053)

### Version 5.1.0-alpha5

- Add support for react-native Windows Cpp/WinRT [#1893]((https://github.com/react-native-community/react-native-video/pull/1893))

### Version 5.1.0-alpha4

- Fix android play/pause bug related to full-screen mode [#1916](https://github.com/react-native-community/react-native-video/pull/1916)

### Version 5.1.0-alpha3

- Improve Android Audio Focus [#1897](https://github.com/react-native-community/react-native-video/pull/1897)

### Version 5.1.0-alpha2

- Added support for full-screen functionality in Android Exoplayer [#1730](https://github.com/react-native-community/react-native-video/pull/1730)

### Version 5.1.0-alpha1

- Fixed Exoplayer doesn't work with mute=true (Android). [#1696](https://github.com/react-native-community/react-native-video/pull/1696)
- Added support for automaticallyWaitsToMinimizeStalling property (iOS) [#1723](https://github.com/react-native-community/react-native-video/pull/1723)
- Bump Exoplayer to 2.10.4, remove deprecated usages of Exoplayer methods (Android). [#1753](https://github.com/react-native-community/react-native-video/pull/1753)
- Preserve Exoplayer BandwidthMeter instance across video plays, this should noticeably improve streaming bandwidth detection (Android).

### Version 5.0.2

- Fix crash when RCTVideo's superclass doesn't observe the keyPath 'frame' (iOS) [#1720](https://github.com/react-native-community/react-native-video/pull/1720)

### Version 5.0.1

- Fix AndroidX Support bad merge

### Version 5.0.0 [Deprecated]

- AndroidX Support

### Version 4.4.4

- Handle racing conditions when props are settled on Exoplayer

### Version 4.4.3

- Fix mute/unmute when controls are present (iOS) [#1654](https://github.com/react-native-community/react-native-video/pull/1654)
- Fix Android videos being able to play with background music/audio from other apps.
- Fixed memory leak on iOS when using `controls` [#1647](https://github.com/react-native-community/react-native-video/pull/1647)
- (Android) Update gradle and target SDK [#1629](https://github.com/react-native-community/react-native-video/pull/1629)
- Fix iOS stressed mount/unmount crash [#1646](https://github.com/react-native-community/react-native-video/pull/1646)

### Version 4.4.2

- Change compileOnly to implementation on gradle (for newer gradle versions and react-native 0.59 support) [#1592](https://github.com/react-native-community/react-native-video/pull/1592)
- Replaced RCTBubblingEventBlock events by RCTDirectEventBlock to avoid event name collisions [#1625](https://github.com/react-native-community/react-native-video/pull/1625)
- Added `onPlaybackRateChange` to README [#1578](https://github.com/react-native-community/react-native-video/pull/1578)
- Added `onReadyForDisplay` to README [#1627](https://github.com/react-native-community/react-native-video/pull/1627)
- Improved handling of poster image. Fixes bug with displaying video and poster simultaneously. [#1627](https://github.com/react-native-community/react-native-video/pull/1627)
- Fix background audio stopping on iOS when using `controls` [#1614](https://github.com/react-native-community/react-native-video/pull/1614)

### Version 4.4.1

- Fix tvOS picture-in-picture compilation regression [#1518](https://github.com/react-native-community/react-native-video/pull/1518)
- fullscreen rotation issues with iOS built-in controls [#1441](https://github.com/react-native-community/react-native-video/pull/1441)
- Fix player freeze when playing audio files on ExoPlayer [#1529](https://github.com/react-native-community/react-native-video/pull/1529)

### Version 4.4.0

- Fix runtime warning by replacing `UIManager.RCTVideo` with `UIManager.getViewManagerConfig('RCTVideo')` (and ensuring backwards compat) [#1487](https://github.com/react-native-community/react-native-video/pull/1487)
- Fix loading package resolved videos when using video-caching [#1438](https://github.com/react-native-community/react-native-video/pull/1438)
- Fix "message sent to deallocated instance" crash on ios [#1482](https://github.com/react-native-community/react-native-video/pull/1482)
- Display a warning when source is empty [#1478](https://github.com/react-native-community/react-native-video/pull/1478)
- Don't crash on iOS for an empty source [#1246](https://github.com/react-native-community/react-native-video/pull/1246)
- Recover from from transient internet failures when loading on ExoPlayer [#1448](https://github.com/react-native-community/react-native-video/pull/1448)
- Add controls support for ExoPlayer [#1414](https://github.com/react-native-community/react-native-video/pull/1414)
- Fix check for text tracks when iOS caching enabled [#1387](https://github.com/react-native-community/react-native-video/pull/1387)
- Add support for Picture in Picture on iOS [#1325](https://github.com/react-native-community/react-native-video/pull/1325)
- Fix UIManager undefined variable [#1488](https://github.com/react-native-community/react-native-video/pull/1488)

### Version 4.3.0

- Fix iOS video not displaying after switching source [#1395](https://github.com/react-native-community/react-native-video/pull/1395)
- Add the filterEnabled flag, fixes iOS video start time regression [#1384](https://github.com/react-native-community/react-native-video/pull/1384)
- Fix text not appearing in release builds of Android apps [#1373](https://github.com/react-native-community/react-native-video/pull/1373)
- Update to ExoPlayer 2.9.3 [#1406](https://github.com/react-native-community/react-native-video/pull/1406)
- Add video track selection & onBandwidthUpdate [#1199](https://github.com/react-native-community/react-native-video/pull/1199)
- Recovery from transient internet failures and props to configure the custom retry count [#1448](https://github.com/react-native-community/react-native-video/pull/1448)

### Version 4.2.0

- Don't initialize filters on iOS unless a filter is set. This was causing a startup performance regression [#1360](https://github.com/react-native-community/react-native-video/pull/1360)
- Support setting the maxBitRate [#1310](https://github.com/react-native-community/react-native-video/pull/1310)
- Fix useTextureView not defaulting to true [#1383](https://github.com/react-native-community/react-native-video/pull/1383)
- Fix crash on MediaPlayer w/ Android 4.4 & avoid memory leak [#1328](https://github.com/react-native-community/react-native-video/pull/1328)

### Version 4.1.0

- Generate onSeek on Android ExoPlayer & MediaPlayer after seek completes [#1351](https://github.com/react-native-community/react-native-video/pull/1351)
- Remove unneeded onVideoSaved event [#1350](https://github.com/react-native-community/react-native-video/pull/1350)
- Disable AirPlay if sidecar text tracks are enabled [#1304](https://github.com/react-native-community/react-native-video/pull/1304)
- Add possibility to remove black screen while video is loading in Exoplayer [#1355](https://github.com/react-native-community/react-native-video/pull/1355)

### Version 4.0.1

- Add missing files to package.json [#1342](https://github.com/react-native-community/react-native-video/pull/1342)

### Version 4.0.0

- Partial support for timed metadata on Android MediaPlayer [#707](https://github.com/react-native-community/react-native-video/pull/707)
- Support video caching for iOS [#955](https://github.com/react-native-community/react-native-video/pull/955)
- Video caching cleanups [#1172](https://github.com/react-native-community/react-native-video/pull/1172)
- Add ipod-library support [#926](https://github.com/react-native-community/react-native-video/pull/926/files)
- Fix crash on ExoPlayer when there are no audio tracks [#1233](https://github.com/react-native-community/react-native-video/pull/1233)
- Reduce package size [#1231](https://github.com/react-native-community/react-native-video/pull/1231)
- Remove unnecessary import in TextTrackType [#1229](https://github.com/react-native-community/react-native-video/pull/1229)
- Prevent flash between poster and video [#1167](https://github.com/react-native-community/react-native-video/pull/1167)
- Support react-native-dom [#1253](https://github.com/react-native-community/react-native-video/pull/1253)
- Update to ExoPlayer 2.8.2. Android SDK 26 now required [#1170](https://github.com/react-native-community/react-native-video/pull/1170)
- Update to ExoPlayer 2.8.4 [#1266](https://github.com/react-native-community/react-native-video/pull/1266)
- Add fullscreenOrientation option for iOS [#1215](https://github.com/react-native-community/react-native-video/pull/1215)
- Update to ExoPlayer 2.9.0 [#1285](https://github.com/react-native-community/react-native-video/pull/1285)
- Switch useTextureView to default to `true` [#1286](https://github.com/react-native-community/react-native-video/pull/1286)
- Re-add fullscreenAutorotate prop [#1303](https://github.com/react-native-community/react-native-video/pull/1303)
- Make seek throw a useful error for NaN values [#1283](https://github.com/react-native-community/react-native-video/pull/1283)
- Video Filters and Save Video [#1306](https://github.com/react-native-community/react-native-video/pull/1306)
- Fix: volume should not change on onAudioFocusChange event [#1327](https://github.com/react-native-community/react-native-video/pull/1327)
- Update ExoPlayer to 2.9.1 and OkHTTP to 3.12.0 [#1338](https://github.com/react-native-community/react-native-video/pull/1338)

### Version 3.2.0

- Basic fullscreen support for Android MediaPlayer [#1138](https://github.com/react-native-community/react-native-video/pull/1138)
- Simplify default Android SDK code [#1145](https://github.com/react-native-community/react-native-video/pull/1145) [#1146](https://github.com/react-native-community/react-native-video/pull/1146)
- Various iOS sideloaded text track fixes [#1157](https://github.com/react-native-community/react-native-video/pull/1157)
- Fix #1150 where assets with bundled assets don't work on iOS in release mode [#1162](https://github.com/react-native-community/react-native-video/pull/1162)
- Support configuring the buffer on Android ExoPlayer [#1160](https://github.com/react-native-community/react-native-video/pull/1160)
- Prevent sleep from sleeping while videos are playing on Android MediaPlayer [#1117](https://github.com/react-native-community/react-native-video/pull/1117)
- Update NewtonSoft JSON to match react-native-windows version [#1169](https://github.com/react-native-community/react-native-video/pull/1169)

### Version 3.1.0

- Support sidecar text tracks on iOS [#1109](https://github.com/react-native-community/react-native-video/pull/1109)
- Support onAudioBecomingNoisy on iOS [#1131](https://github.com/react-native-community/react-native-video/pull/1131)

### Version 3.0

- Inherit Android buildtools and SDK version from the root project [#1081](https://github.com/react-native-community/react-native-video/pull/1081)
- Automatically play on ExoPlayer when the paused prop is not set [#1083](https://github.com/react-native-community/react-native-video/pull/1083)
- Preserve Android MediaPlayer paused prop when backgrounding [#1082](https://github.com/react-native-community/react-native-video/pull/1082)
- Support specifying headers on ExoPlayer as part of the source [#805](https://github.com/react-native-community/react-native-video/pull/805)
- Prevent iOS onLoad event during seeking [#1088](https://github.com/react-native-community/react-native-video/pull/1088)
- ExoPlayer playableDuration incorrect [#1089](https://github.com/react-native-community/react-native-video/pull/1089)

### Version 2.3.1

- Revert PR to inherit Android SDK versions from root project. Re-add in 3.0 [#1080](https://github.com/react-native-community/react-native-video/pull/1080)

### Version 2.3.0

- Support allowsExternalPlayback on iOS [#1057](https://github.com/react-native-community/react-native-video/pull/1057)
- Inherit Android buildtools and SDK version from the root project [#999](https://github.com/react-native-community/react-native-video/pull/999)
- Fix bug that caused ExoPlayer to start paused if playInBackground was set [#833](https://github.com/react-native-community/react-native-video/pull/833)
- Fix crash if clearing an observer on iOS that was already cleared [#1075](https://github.com/react-native-community/react-native-video/pull/1075)
- Add audioOnly prop for music files [#1039](https://github.com/react-native-community/react-native-video/pull/1039)
- Support seeking with more exact tolerance on iOS [#1076](https://github.com/react-native-community/react-native-video/pull/1076)

### Version 2.2.0

- Text track selection support for iOS & ExoPlayer [#1049](https://github.com/react-native-community/react-native-video/pull/1049)
- Support outputting to a TextureView on Android ExoPlayer [#1058](https://github.com/react-native-community/react-native-video/pull/1058)
- Support changing the left/right balance on Android MediaPlayer [#1051](https://github.com/react-native-community/react-native-video/pull/1051)
- Prevent multiple onEnd notifications on iOS [#832](https://github.com/react-native-community/react-native-video/pull/832)
- Fix doing a partial swipe on iOS causing a black screen [#1048](https://github.com/react-native-community/react-native-video/pull/1048)
- Fix crash when switching to a new source on iOS [#974](https://github.com/react-native-community/react-native-video/pull/974)
- Add cookie support for ExoPlayer [#922](https://github.com/react-native-community/react-native-video/pull/922)
- Remove ExoPlayer onMetadata that wasn't being used [#1040](https://github.com/react-native-community/react-native-video/pull/1040)
- Fix bug where setting the progress interval on iOS didn't work [#800](https://github.com/react-native-community/react-native-video/pull/800)
- Support setting the poster resize mode [#595](https://github.com/react-native-community/react-native-video/pull/595)