#### 0.2.0 (2019-02-09)

##### Documentation Changes

*  update issue templates ([67abcf6c](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/67abcf6c8a392834e33e71346a1390b2cf5ebe74))

##### New Features

*  implement ussd push webhook result parser ([42320c69](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/42320c69d1f7c598909dbc4fd3f8dcca830998e3))

#### 0.1.0 (2019-02-09)

##### Chores

*  upgrade to travis to node >=11.7.0 ([9b8147b4](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/9b8147b40b99d5e123b7a27dd8059142f0bb787f))
*  update source jsdocs ([15b65c64](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/15b65c640ccd404bde110fb789da5789fbdd5529))

##### Documentation Changes

*  improve usage docs ([451f187a](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/451f187ae448fae20d3ddc3b0e33187025229e2a))
*  update usage docs ([5b0e5953](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/5b0e59535ffe474665a8dae6aebd0d9e71cea990))

##### New Features

*  implement request payment ([e36a6d6e](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/e36a6d6e3c9003b07c3b45ce542c4182f4614e8c))
*  deserialize authentication failed, login failed & session expired to error ([d551f8e1](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/d551f8e1f3c7d8dd3890c69d9983eda983639c9f))
*  implement ussd login request ([61d13969](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/61d13969905e71a4763def7595531dbdf5599510))
*  implement transaction response deserializer ([d0a93ef0](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/d0a93ef0629c1d83bbbbc33a0e92a37cbe6863bf))
*  implement login response deserialize ([1583d9bd](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/1583d9bd37036a94cd6f4942c2a0101ce24f329a))
*  implement transaction request payload builder ([d2159f30](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/d2159f30bc474356a0846b2486fc7499271eb8a2))
*  implement login request builder ([9c02642a](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/9c02642a9e75d91d7d416120a7d2d4f0e61738f2))
*  implement request xml builder ([e341ac5a](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/e341ac5a3866a426e8157d00a1039e9b18845af1))
*  implement parseTransactionResult ([97d24801](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/97d248011faa5e4b89b8aa830c15eea187561613))
*  implement gereric request parse ([208685ed](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/208685edf94402f58dc1c0e16b49d3f8ebae4731))
*  add currency client metadata ([e06dd19c](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/e06dd19c74fdb1119e9b8346f782dba62230143b))
*  add client required metadata ([8a614efa](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/8a614efacdb6f5e3ca02d176a9575dba326d74c2))

##### Refactors

*  serializeTransaction to merge defaults ([4e733b9e](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/4e733b9e615db990425743136a2171d916edcd71))
*  serializeLogin to merge defaults ([9d061ea8](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/9d061ea86a4ba36aa9c3f7f2ccfcc205a0346d64))
*  rename token to sessionId for transaction serialization ([f8cf740d](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/f8cf740d78c5f93f26acc2fef28c4ae0ec0c9204))
*  rename parseTransactionResult to deserializeResult ([c99932b5](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/c99932b5f05cc62f55f14925bf8cd9e8e05a5d76))
*  rename parseTransactionResponse to deserializeTransaction ([c8ba0adb](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/c8ba0adba8180bd5a3ebc180d1551859b5bbfe33))
*  rename parseLoginResponse to deserializeLogin ([4e2f9230](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/4e2f9230f178048be1af1e278998bbafa8b384bc))
*  rename parseRequest to deserialize ([31798018](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/31798018ac15a665486fa1ee05c26769fe4b47d3))
*  rename buildTransactionRequest to serializeTransaction ([0657e738](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/0657e73824a3ae6a861cbdb50ee122826706322c))
*  rename buildLoginRequest to serializeLogin ([a83105d2](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/a83105d2881a2fd1027d856b6b0593fc250af56b))
*  rename buildRequest to serialize ([7cc0a147](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/7cc0a147f8ac73f873170b996f69cea5a3c2bfa0))
*  rename parseRequest->parseXml & buildRequest->buildXml ([a34718e7](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/a34718e72eea917a0ba0b3173033243b584280c1))

##### Tests

*  review charge specs ([04c94c49](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/04c94c496721e1bc28fefe78fe1aa00576e2848f))
*  implement transaction error specs ([4973a776](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/4973a776a4cf5913744c6de05cef34bfd7a89667))
*  refactor to add default env variables ([b185de16](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/b185de16bbd8b8e3b5b2f026fde9faa205f3e1e2))
*  refactor readFile to helper ([afa8a9bc](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/afa8a9bca072a714eeb07fd20c712d8f8650f69e))
*  improve login specs for auth failed, session expired & login failed ([ad561fb9](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/ad561fb90760a3baa4ce7c018f2875c7137277d3))
*  improve login error handlers specs ([4db09d4e](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/4db09d4ee3ffd87a18e6b176744b2a90a7db2873))
*  rename transaction result title ([e217782f](https://github.com/lykmapipo/tz-mpesa-ussd-push/commit/e217782f97277e5aefd033bf014dc709827d648c))

