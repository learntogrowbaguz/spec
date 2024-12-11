## [1.3.2](https://github.com/open-rpc/spec/compare/1.3.1...1.3.2) (2023-07-04)


### Bug Fixes

* examplePairingObject.name and params are required in the metaschema ([3cdace9](https://github.com/open-rpc/spec/commit/3cdace9c208d2874d0b966c73687defc7ba40990))

## [1.3.1](https://github.com/open-rpc/spec/compare/1.3.0...1.3.1) (2023-02-06)


### Bug Fixes

* add a note about examplePairingObject.result being undefined ([30aee1b](https://github.com/open-rpc/spec/commit/30aee1b5186d623f197b4f31cb6152bc0bbd23c0))
* tests borked up ([5f73e6e](https://github.com/open-rpc/spec/commit/5f73e6e157b01b17a7790050c886e70957b4646a))

# [1.3.0](https://github.com/open-rpc/spec/compare/1.2.6...1.3.0) (2023-02-01)


### Bug Fixes

* bump node version and update circle config ([52403aa](https://github.com/open-rpc/spec/commit/52403aabd8eb0a2a6cd52ecfe10d7e48b9b4dcde))
* dont point to latest json schema  ([114202c](https://github.com/open-rpc/spec/commit/114202cf52ce1b0d196d816551aec2e64f0e4230)), closes [#330](https://github.com/open-rpc/spec/issues/330)
* follow conventional capitalization pattern ([bb3b838](https://github.com/open-rpc/spec/commit/bb3b838d61f2c5c5cf194183ea6015d76e54bdb5))
* markdown inside html doenst work ([664eec1](https://github.com/open-rpc/spec/commit/664eec189eb19f684913b8517f82ab4c1a2b6bc1))
* missing bracket  ([8f6e649](https://github.com/open-rpc/spec/commit/8f6e6497d45a5d15db1c389ff1cb1992334887fe))
* re-order release perparation steps ([4893ac8](https://github.com/open-rpc/spec/commit/4893ac88b623b6af188c500c7d6445734252aa2d)), closes [#292](https://github.com/open-rpc/spec/issues/292)
* remove example object referencing content descriptor use ([b9f00de](https://github.com/open-rpc/spec/commit/b9f00de8d48494944b04762bca0095cfffab9b91)), closes [/github.com/open-rpc/spec/issues/315#issuecomment-718258896](https://github.com//github.com/open-rpc/spec/issues/315/issues/issuecomment-718258896)
* s/supercedes/supersedes/ ([91533e3](https://github.com/open-rpc/spec/commit/91533e30e997581ba84c2966c500c30afb92d59b))
* shamelessly add funding link via open collective ([c3f8de2](https://github.com/open-rpc/spec/commit/c3f8de27cd85d19fd68e1e5fa65b8213e935ca88))
* typo in Example Object ([c551b21](https://github.com/open-rpc/spec/commit/c551b2128d40a333ed307ae7c608f065e77fe505))
* update discord link ([d75ceeb](https://github.com/open-rpc/spec/commit/d75ceeb6a8ee23fcb29e83993c4cb3e4016d745a))
* update labler to v4 ([cd3ac52](https://github.com/open-rpc/spec/commit/cd3ac52959f97ced96c7a7c38983e4b0771879e7))


### Features

* add support for strict notification methods ([a9a3091](https://github.com/open-rpc/spec/commit/a9a30917983c1efe417cd72825559896db19fbe1)), closes [#230](https://github.com/open-rpc/spec/issues/230)

## [1.2.6](https://github.com/open-rpc/spec/compare/1.2.5...1.2.6) (2020-05-22)


### Bug Fixes

* schema required formatting ([1a745b5](https://github.com/open-rpc/spec/commit/1a745b51fd97fc4645d2ec2fd0196b634525ceec))
* **method.paramStructure:** add spec detailing by-name case of cd.name ([646978c](https://github.com/open-rpc/spec/commit/646978cb550cf336cce1bbad5634263b4f74d6c4))
* [@belfordz](https://github.com/belfordz) edits for awesomeness ([cbae9e3](https://github.com/open-rpc/spec/commit/cbae9e3165f28e3c9d716a23d76e0a1ac832844a))
* add another oxford comma ([b1092f6](https://github.com/open-rpc/spec/commit/b1092f699ed7d5f843eeaaccd181416087b1fc08))
* append 's' to param_s_ field ([9da993b](https://github.com/open-rpc/spec/commit/9da993be2644f8e2461d8daf2d408e9242cd634b))
* formatting of required on linkObject.name ([63f5410](https://github.com/open-rpc/spec/commit/63f5410217bb15f90ae7dc88a5f54b99cdc7f21c))
* missing oxford comma ([df8a507](https://github.com/open-rpc/spec/commit/df8a507327d513a4806aa5176bab9d474d813b4c))
* non-oxfordian missing space after oxfordian comma ([1deef5c](https://github.com/open-rpc/spec/commit/1deef5cffc69e3448bdd95a05ab92b50fd26bc13))
* remove oneOf ([215b0ae](https://github.com/open-rpc/spec/commit/215b0ae28ef6b7951f1e0d88fee904906da47d27)), closes [#278](https://github.com/open-rpc/spec/issues/278)
* remove unused dev deps ([11df1e8](https://github.com/open-rpc/spec/commit/11df1e847c2de50f8d4b24fd996206b7c335a19b))
* s/field/value ([75275e6](https://github.com/open-rpc/spec/commit/75275e6cd7bd6980d01e4ad42904ea6d1cba2026))
* update FAQ and add to repo ([7c7310c](https://github.com/open-rpc/spec/commit/7c7310c3e660279ab4411680b5afb562bc7a3c84)), closes [#283](https://github.com/open-rpc/spec/issues/283)

## [1.2.5](https://github.com/open-rpc/spec/compare/1.2.4...1.2.5) (2020-05-06)


### Bug Fixes

* default paramStructure to either ([558241f](https://github.com/open-rpc/spec/commit/558241fbb25cc59baaa0b3782078e9d4bc470467)), closes [#270](https://github.com/open-rpc/spec/issues/270)

## [1.2.4](https://github.com/open-rpc/spec/compare/1.2.3...1.2.4) (2019-12-20)


### Bug Fixes

* set private to true in package json to avoid publishing ([1ff411a](https://github.com/open-rpc/spec/commit/1ff411af447d255705cde16d1f7f9cbcbeafebb7))
* version fix take 4 ([844eccc](https://github.com/open-rpc/spec/commit/844eccc31d475e55c39e006e05b7b0e9287983fd))

## [1.2.3](https://github.com/open-rpc/spec/compare/1.2.2...1.2.3) (2019-12-20)


### Bug Fixes

* missing run command ([b4144f9](https://github.com/open-rpc/spec/commit/b4144f9c464ca57cf64dacb34591405ef8cff8bb))
* second attempt at getting version fixed ([b12c828](https://github.com/open-rpc/spec/commit/b12c828426b1da52b4418f769c57af05c8950641))
* third attempt at fixing version ([9758c93](https://github.com/open-rpc/spec/commit/9758c9309ef71b8f024f70c52cd663b14a0e2449))
* update definitions and remove the word schema ([4577270](https://github.com/open-rpc/spec/commit/4577270379ed96985ba1d8c6fddbfd7349880446))

## [1.2.2](https://github.com/open-rpc/spec/compare/1.2.1...1.2.2) (2019-12-20)


### Bug Fixes

* restore package.json ([9e108bf](https://github.com/open-rpc/spec/commit/9e108bfb0c65931a817cf43774360bdf0c561fda))
* semantic-release fixups ([c8b33e5](https://github.com/open-rpc/spec/commit/c8b33e5adc2ead057cc6c59f3e4528b6d398c3ef))
* set version properly ([daf2a82](https://github.com/open-rpc/spec/commit/daf2a8234b7044bfe0bcc4e97dcfc251b4bd12fb)), closes [#191](https://github.com/open-rpc/spec/issues/191)
* update build accordingly ([af8fe8d](https://github.com/open-rpc/spec/commit/af8fe8d8043736703e442ec73f70cc58edb9c2d6))

## [1.2.1](https://github.com/open-rpc/spec/compare/1.2.0...1.2.1) (2019-09-26)


### Bug Fixes

* add "either" option for param structure ([947c12b](https://github.com/open-rpc/spec/commit/947c12b)), closes [#190](https://github.com/open-rpc/spec/issues/190) [#226](https://github.com/open-rpc/spec/issues/226)

# [1.2.0](https://github.com/open-rpc/spec/compare/1.1.12...1.2.0) (2019-09-23)


### Bug Fixes

* checkout package after installing semanticrel ([a9d5841](https://github.com/open-rpc/spec/commit/a9d5841))
* remove additional dash ([0674aaf](https://github.com/open-rpc/spec/commit/0674aaf))
* remove sem rel deps last time ([5388f19](https://github.com/open-rpc/spec/commit/5388f19))
* remove sponsor ([85c83e1](https://github.com/open-rpc/spec/commit/85c83e1))


### Features

* add first set of labels ([5c86521](https://github.com/open-rpc/spec/commit/5c86521))
* add greetings action ([8bccaf3](https://github.com/open-rpc/spec/commit/8bccaf3))
* add labler action ([74b1909](https://github.com/open-rpc/spec/commit/74b1909))

## [1.1.12](https://github.com/open-rpc/spec/compare/1.1.11...1.1.12) (2019-07-30)


### Bug Fixes

* **circle:** add build ([4c3ae15](https://github.com/open-rpc/spec/commit/4c3ae15))

## [1.1.11](https://github.com/open-rpc/spec/compare/1.1.10...1.1.11) (2019-07-30)


### Bug Fixes

* install semantic release in circle ([641562f](https://github.com/open-rpc/spec/commit/641562f))
* remove semantic release from packagejson ([d799ce2](https://github.com/open-rpc/spec/commit/d799ce2))
* update package lock ([c6ecb2a](https://github.com/open-rpc/spec/commit/c6ecb2a))

## [1.1.10](https://github.com/open-rpc/spec/compare/1.1.9...1.1.10) (2019-06-04)


### Bug Fixes

* Require optional params to follow required params ([a031e71](https://github.com/open-rpc/spec/commit/a031e71)), closes [#188](https://github.com/open-rpc/spec/issues/188)

## [1.1.9](https://github.com/open-rpc/spec/compare/1.1.8...1.1.9) (2019-05-15)


### Bug Fixes

* change type of MethodObject.name to string ([2282b29](https://github.com/open-rpc/spec/commit/2282b29)), closes [#180](https://github.com/open-rpc/spec/issues/180)
* typo ([ef7b956](https://github.com/open-rpc/spec/commit/ef7b956))
* typo in a Map description ([247f298](https://github.com/open-rpc/spec/commit/247f298))

## [1.1.8](https://github.com/open-rpc/spec/compare/1.1.7...1.1.8) (2019-04-27)


### Bug Fixes

* **methodObject:** optional params recommendation ([5d614b2](https://github.com/open-rpc/spec/commit/5d614b2)), closes [#138](https://github.com/open-rpc/spec/issues/138)

## [1.1.7](https://github.com/open-rpc/spec/compare/1.1.6...1.1.7) (2019-04-23)


### Bug Fixes

* add OneOf object to result ([d905538](https://github.com/open-rpc/spec/commit/d905538)), closes [#170](https://github.com/open-rpc/spec/issues/170)
* release ([4544160](https://github.com/open-rpc/spec/commit/4544160))

## [1.1.6](https://github.com/open-rpc/spec/compare/1.1.5...1.1.6) (2019-04-18)


### Bug Fixes

* build filter get-version ([0fc9ef8](https://github.com/open-rpc/spec/commit/0fc9ef8))
* cleanup ([23a0ff4](https://github.com/open-rpc/spec/commit/23a0ff4))
* formatting ([e8aea3d](https://github.com/open-rpc/spec/commit/e8aea3d))
* make obvious that version isnt real ([e38cfc0](https://github.com/open-rpc/spec/commit/e38cfc0))
* release version templated ([141d4e3](https://github.com/open-rpc/spec/commit/141d4e3))
* **toc:** build working again ([5ae4e66](https://github.com/open-rpc/spec/commit/5ae4e66))
* remove build from ci ([2dbe3f9](https://github.com/open-rpc/spec/commit/2dbe3f9))
* update scripts ([9f13be6](https://github.com/open-rpc/spec/commit/9f13be6))
* versioned latest url ([ff4bcc8](https://github.com/open-rpc/spec/commit/ff4bcc8))

## [1.1.5](https://github.com/open-rpc/spec/compare/1.1.4...1.1.5) (2019-04-08)


### Bug Fixes

* **release:** try again ([7ba538d](https://github.com/open-rpc/spec/commit/7ba538d))

## [1.1.4](https://github.com/open-rpc/spec/compare/1.1.3...1.1.4) (2019-04-08)


### Bug Fixes

* gitignore build properly ([b2eb08d](https://github.com/open-rpc/spec/commit/b2eb08d))
* release plugins ([8050a74](https://github.com/open-rpc/spec/commit/8050a74))
* remove build folder ([b02fe72](https://github.com/open-rpc/spec/commit/b02fe72))

## [1.1.2](https://github.com/open-rpc/spec/compare/1.1.1...1.1.2) (2019-04-08)


### Bug Fixes

* release not uploading artifacts ([6a9c721](https://github.com/open-rpc/spec/commit/6a9c721))

## [1.1.1](https://github.com/open-rpc/spec/compare/1.1.0...1.1.1) (2019-04-08)


### Bug Fixes

* add success and fail handler to release ([589db49](https://github.com/open-rpc/spec/commit/589db49))
* **release:** indicate commit messages generated ([8c34567](https://github.com/open-rpc/spec/commit/8c34567))
* **releaserc:** tighten commit message sign off ([b06a454](https://github.com/open-rpc/spec/commit/b06a454))

# [1.1.0](https://github.com/open-rpc/spec/compare/1.0.0...1.1.0) (2019-04-07)


### Bug Fixes

* gh release artifact name ([a38601d](https://github.com/open-rpc/spec/commit/a38601d))


### Features

* add link for latest version of spec ([ce8ecf0](https://github.com/open-rpc/spec/commit/ce8ecf0))

# 1.0.0 (2019-04-01)


### Bug Fixes

* add alt to logo ([37898f3](https://github.com/open-rpc/spec/commit/37898f3))
* add description for contentDescriptors ([e65b691](https://github.com/open-rpc/spec/commit/e65b691))
* add empty job ([0691234](https://github.com/open-rpc/spec/commit/0691234))
* add error to method ([a12b656](https://github.com/open-rpc/spec/commit/a12b656))
* add example in schema case ([5e61cca](https://github.com/open-rpc/spec/commit/5e61cca))
* add extra explanation ([791cf11](https://github.com/open-rpc/spec/commit/791cf11))
* add info about examples and meta schema ([8623dea](https://github.com/open-rpc/spec/commit/8623dea))
* add markdownlint ([ea6994b](https://github.com/open-rpc/spec/commit/ea6994b)), closes [#148](https://github.com/open-rpc/spec/issues/148)
* add name and summary to Link Object ([cafd56b](https://github.com/open-rpc/spec/commit/cafd56b)), closes [#127](https://github.com/open-rpc/spec/issues/127)
* add pairing name ([299d523](https://github.com/open-rpc/spec/commit/299d523))
* add param structure field to support json rpc accurately ([e848fe6](https://github.com/open-rpc/spec/commit/e848fe6))
* add required to errorObject fields ([8d295de](https://github.com/open-rpc/spec/commit/8d295de)), closes [#104](https://github.com/open-rpc/spec/issues/104)
* add video guide for making small documentation changes ([687692d](https://github.com/open-rpc/spec/commit/687692d))
* always use examples as array ([9c31f53](https://github.com/open-rpc/spec/commit/9c31f53))
* better definitions ([aca0dff](https://github.com/open-rpc/spec/commit/aca0dff))
* capitalize must ([3a55a0f](https://github.com/open-rpc/spec/commit/3a55a0f))
* capitlization fix ([36724ca](https://github.com/open-rpc/spec/commit/36724ca))
* center sponsored by ([52c63e0](https://github.com/open-rpc/spec/commit/52c63e0))
* change discovery to discover ([149b79c](https://github.com/open-rpc/spec/commit/149b79c))
* change discovery to discover ([be98ab4](https://github.com/open-rpc/spec/commit/be98ab4))
* change name of runtime expressions standard ([de484d1](https://github.com/open-rpc/spec/commit/de484d1))
* change name to pairing from mapping ([3856cc9](https://github.com/open-rpc/spec/commit/3856cc9))
* components cant be reference objects ([9496962](https://github.com/open-rpc/spec/commit/9496962))
* content descriptor object required default ([11ccc36](https://github.com/open-rpc/spec/commit/11ccc36))
* content-descriptor-object link ([7d3c257](https://github.com/open-rpc/spec/commit/7d3c257))
* contentDescriptor over parametersObject ([eb986c3](https://github.com/open-rpc/spec/commit/eb986c3))
* define JSON String templating language for template strings ([8437e18](https://github.com/open-rpc/spec/commit/8437e18))
* descriptions shouldnt read 'a short description' ([66425b1](https://github.com/open-rpc/spec/commit/66425b1))
* desired values text for runtime expression ([435abb9](https://github.com/open-rpc/spec/commit/435abb9))
* discovery to reflect JSON RPC spec ([225ea77](https://github.com/open-rpc/spec/commit/225ea77))
* dont center examplePairingObject ([c24c1cc](https://github.com/open-rpc/spec/commit/c24c1cc)), closes [#110](https://github.com/open-rpc/spec/issues/110)
* dont use method text in content descriptor ([4a3cd0c](https://github.com/open-rpc/spec/commit/4a3cd0c)), closes [#109](https://github.com/open-rpc/spec/issues/109)
* error docs meaning field to data ([336873e](https://github.com/open-rpc/spec/commit/336873e))
* errors ([c881703](https://github.com/open-rpc/spec/commit/c881703))
* example params may be a reference object ([704d14a](https://github.com/open-rpc/spec/commit/704d14a))
* example-object result ([2ad2987](https://github.com/open-rpc/spec/commit/2ad2987))
* fix ci ([31eded4](https://github.com/open-rpc/spec/commit/31eded4))
* fix extra whitespace ([d91bf21](https://github.com/open-rpc/spec/commit/d91bf21))
* fix indentation ([14b6635](https://github.com/open-rpc/spec/commit/14b6635))
* fix missing quotes around methods ([67dd189](https://github.com/open-rpc/spec/commit/67dd189))
* fixup remaining errors ([481abfc](https://github.com/open-rpc/spec/commit/481abfc))
* fixups ([d187d26](https://github.com/open-rpc/spec/commit/d187d26))
* formatting on server vars ([2194c76](https://github.com/open-rpc/spec/commit/2194c76))
* incorrect methods example ([37c2753](https://github.com/open-rpc/spec/commit/37c2753))
* invalid json and typos ([e32ff7c](https://github.com/open-rpc/spec/commit/e32ff7c))
* json broken ([ace1fc0](https://github.com/open-rpc/spec/commit/ace1fc0))
* JSON-RPC over JSON RPC ([3b04e68](https://github.com/open-rpc/spec/commit/3b04e68))
* keep APIs wording use consistent ([e4310f4](https://github.com/open-rpc/spec/commit/e4310f4))
* left over dasherizing ([01900d4](https://github.com/open-rpc/spec/commit/01900d4))
* link request param fix ([b93e2f5](https://github.com/open-rpc/spec/commit/b93e2f5))
* links example + contentDescriptor example + method example ([a7ff97d](https://github.com/open-rpc/spec/commit/a7ff97d))
* links in method ([24646ee](https://github.com/open-rpc/spec/commit/24646ee))
* links should be arrays ([081aa23](https://github.com/open-rpc/spec/commit/081aa23))
* lint fixes ([05f5f87](https://github.com/open-rpc/spec/commit/05f5f87))
* localhost if server is empty ([4f942b3](https://github.com/open-rpc/spec/commit/4f942b3))
* lowercase error field names ([948f535](https://github.com/open-rpc/spec/commit/948f535))
* messed up spacing ([2cdc1f4](https://github.com/open-rpc/spec/commit/2cdc1f4))
* method over operation ([546275d](https://github.com/open-rpc/spec/commit/546275d))
* method params ([9e721f8](https://github.com/open-rpc/spec/commit/9e721f8))
* method servers ([25d4304](https://github.com/open-rpc/spec/commit/25d4304))
* method-examples link and description ([7f9da28](https://github.com/open-rpc/spec/commit/7f9da28))
* methodObject tag link ([b3f9bd6](https://github.com/open-rpc/spec/commit/b3f9bd6))
* methods should be method ([9881f8f](https://github.com/open-rpc/spec/commit/9881f8f))
* move conventions and resource up in the readme ([95fe209](https://github.com/open-rpc/spec/commit/95fe209))
* move to pristine ([16470f1](https://github.com/open-rpc/spec/commit/16470f1))
* nameExample JSON syntax error ([5d0f799](https://github.com/open-rpc/spec/commit/5d0f799))
* reference json schema for $refs ([c26b217](https://github.com/open-rpc/spec/commit/c26b217))
* reference to openapi ([157d238](https://github.com/open-rpc/spec/commit/157d238))
* remove a level of header indent ([0f7a0b4](https://github.com/open-rpc/spec/commit/0f7a0b4))
* remove comment about organization ([f1a3347](https://github.com/open-rpc/spec/commit/f1a3347))
* remove datatypes and defer to json schema spec ([2c4a895](https://github.com/open-rpc/spec/commit/2c4a895))
* remove document structure ([b863f5f](https://github.com/open-rpc/spec/commit/b863f5f))
* remove examples from spec ([9acf1c1](https://github.com/open-rpc/spec/commit/9acf1c1)), closes [#123](https://github.com/open-rpc/spec/issues/123)
* remove extra stuff ([#7](https://github.com/open-rpc/spec/issues/7)) ([2bcaa35](https://github.com/open-rpc/spec/commit/2bcaa35))
* remove hard tabs rule ([10efb9a](https://github.com/open-rpc/spec/commit/10efb9a))
* remove header a tag wrappers ([3bc7ba7](https://github.com/open-rpc/spec/commit/3bc7ba7))
* remove left over a wrapper ([ffd8f23](https://github.com/open-rpc/spec/commit/ffd8f23))
* remove linkRequest ([04e9327](https://github.com/open-rpc/spec/commit/04e9327))
* remove old cname file ([aeb85a3](https://github.com/open-rpc/spec/commit/aeb85a3))
* remove old license ([54950a2](https://github.com/open-rpc/spec/commit/54950a2))
* remove references to anything yaml related ([6e90463](https://github.com/open-rpc/spec/commit/6e90463))
* remove trash files ([0e2c660](https://github.com/open-rpc/spec/commit/0e2c660))
* remove travis.yml ([#9](https://github.com/open-rpc/spec/issues/9)) ([71be1bf](https://github.com/open-rpc/spec/commit/71be1bf))
* remove unneeded schema spec duplication ([a542cd9](https://github.com/open-rpc/spec/commit/a542cd9))
* remove whitespace rule ([9118866](https://github.com/open-rpc/spec/commit/9118866))
* Rename LICENSE -> LICENSE.md ([6389e32](https://github.com/open-rpc/spec/commit/6389e32))
* replace github for Github ([161f729](https://github.com/open-rpc/spec/commit/161f729))
* result over response ([bcbc3a7](https://github.com/open-rpc/spec/commit/bcbc3a7))
* results and params docs busted ([91076e8](https://github.com/open-rpc/spec/commit/91076e8))
* results in link example ([4894a77](https://github.com/open-rpc/spec/commit/4894a77))
* results is now result ([71f3010](https://github.com/open-rpc/spec/commit/71f3010))
* revert example changes ([a333a7a](https://github.com/open-rpc/spec/commit/a333a7a))
* rewriting existing JSON-RPC API clarification ([9d7d53d](https://github.com/open-rpc/spec/commit/9d7d53d))
* runtime expression table ([2f38638](https://github.com/open-rpc/spec/commit/2f38638))
* schema required on contentDescriptorObject ([46efa4d](https://github.com/open-rpc/spec/commit/46efa4d)), closes [#126](https://github.com/open-rpc/spec/issues/126)
* server needs name ([a1ca601](https://github.com/open-rpc/spec/commit/a1ca601))
* suggestion required link name ([1e29076](https://github.com/open-rpc/spec/commit/1e29076))
* table misformated ([928a8c8](https://github.com/open-rpc/spec/commit/928a8c8))
* tags shouldnt be in root ([58c914b](https://github.com/open-rpc/spec/commit/58c914b))
* typo in CONTRIBUTING.md and compose command in BUILDING.md ([19f68fa](https://github.com/open-rpc/spec/commit/19f68fa))
* unescaped by-position ([8f264ae](https://github.com/open-rpc/spec/commit/8f264ae)), closes [#90](https://github.com/open-rpc/spec/issues/90)
* unique error codes ([3205b7d](https://github.com/open-rpc/spec/commit/3205b7d))
* update BUILDING.md ([02d18c5](https://github.com/open-rpc/spec/commit/02d18c5))
* update BUILDING.md typo ([e89ef99](https://github.com/open-rpc/spec/commit/e89ef99))
* update CONTRIBUTING.md adding docs ([944931c](https://github.com/open-rpc/spec/commit/944931c))
* update CONTRIBUTING.md choppy code changes and testing ([84b8d67](https://github.com/open-rpc/spec/commit/84b8d67))
* update CONTRIBUTING.md grammer around preview markdown ([cbce371](https://github.com/open-rpc/spec/commit/cbce371))
* update CONTRIBUTING.md how to fork a repo ([b2df0bb](https://github.com/open-rpc/spec/commit/b2df0bb))
* update CONTRIBUTING.md to get rid of cloning or forking ([cd0aeeb](https://github.com/open-rpc/spec/commit/cd0aeeb))
* update CONTRIBUTING.md typo ([339fee5](https://github.com/open-rpc/spec/commit/339fee5))
* update link to template language ([f8dafd1](https://github.com/open-rpc/spec/commit/f8dafd1))
* update README introduction list formatting ([adedd85](https://github.com/open-rpc/spec/commit/adedd85))
* update README.md remove YAML ([69a4dd0](https://github.com/open-rpc/spec/commit/69a4dd0))
* update README.md simplify open source grammar ([fe4111f](https://github.com/open-rpc/spec/commit/fe4111f))
* update README.md typo its ([832ca2c](https://github.com/open-rpc/spec/commit/832ca2c))
* updated README ([11d4da2](https://github.com/open-rpc/spec/commit/11d4da2))
* updated README ([#2](https://github.com/open-rpc/spec/issues/2)) ([16f8f29](https://github.com/open-rpc/spec/commit/16f8f29))
* use Github Flavored Markdown ([f3303cf](https://github.com/open-rpc/spec/commit/f3303cf))
* use OpenRPC over OPENRPC ([3ffabba](https://github.com/open-rpc/spec/commit/3ffabba)), closes [#20](https://github.com/open-rpc/spec/issues/20)
* use raw link for etc labs logo ([5f52284](https://github.com/open-rpc/spec/commit/5f52284))
* **build:** add script ([ed511e1](https://github.com/open-rpc/spec/commit/ed511e1))
* **components:** add examplePairingObjects ([f7e735d](https://github.com/open-rpc/spec/commit/f7e735d)), closes [#98](https://github.com/open-rpc/spec/issues/98)
* **components:** add tagObject ([d449c8a](https://github.com/open-rpc/spec/commit/d449c8a)), closes [#99](https://github.com/open-rpc/spec/issues/99)
* **contentDescriptor:** name is required ([41927d8](https://github.com/open-rpc/spec/commit/41927d8)), closes [#88](https://github.com/open-rpc/spec/issues/88)
* use runtime expression for server.url ([967f1b3](https://github.com/open-rpc/spec/commit/967f1b3))
* **examplePairing:** fix table formatting ([82bc779](https://github.com/open-rpc/spec/commit/82bc779))
* use runtime expression as type for server url ([d932d0e](https://github.com/open-rpc/spec/commit/d932d0e))
* wip ([ea774c7](https://github.com/open-rpc/spec/commit/ea774c7))
* **versions:** formatting issues resolved ([bc26551](https://github.com/open-rpc/spec/commit/bc26551))
* wrong brackets ([32f5fb9](https://github.com/open-rpc/spec/commit/32f5fb9))
* **examples:** add a link to the examples ([2f378b9](https://github.com/open-rpc/spec/commit/2f378b9))
* **format:** more specific about patterned field uniqueness ([3654295](https://github.com/open-rpc/spec/commit/3654295))
* **methodObject:** change parameters to params ([89f4692](https://github.com/open-rpc/spec/commit/89f4692)), closes [#117](https://github.com/open-rpc/spec/issues/117)
* **methodObject:** method name is required ([84c8ded](https://github.com/open-rpc/spec/commit/84c8ded)), closes [#118](https://github.com/open-rpc/spec/issues/118)
* **methodObject:** params are required ([99995a5](https://github.com/open-rpc/spec/commit/99995a5)), closes [#108](https://github.com/open-rpc/spec/issues/108)
* **server-description:** typo with github md link ([9a4e957](https://github.com/open-rpc/spec/commit/9a4e957))
* **serverObject:** add summary ([544b174](https://github.com/open-rpc/spec/commit/544b174)), closes [#108](https://github.com/open-rpc/spec/issues/108)
* **tagObject:** add summary ([d868c3f](https://github.com/open-rpc/spec/commit/d868c3f))
* **versions:** consistent use of x ([3df1d5c](https://github.com/open-rpc/spec/commit/3df1d5c))
* **versions:** remove extra words ([a2558ba](https://github.com/open-rpc/spec/commit/a2558ba))


### Features

* add description and pairing to examples ([c76b852](https://github.com/open-rpc/spec/commit/c76b852))
* add empty circle ci config ([cf7f746](https://github.com/open-rpc/spec/commit/cf7f746))
* add examples mapping object ([3b4294a](https://github.com/open-rpc/spec/commit/3b4294a))
* add mdv checking to circleci ([7f217ff](https://github.com/open-rpc/spec/commit/7f217ff))
* add more resources to README ([0a0e5b4](https://github.com/open-rpc/spec/commit/0a0e5b4))
* add oneOf to the spec ([966cea0](https://github.com/open-rpc/spec/commit/966cea0))
* add probot ([66f591b](https://github.com/open-rpc/spec/commit/66f591b))
* add resources for documentation driven development ([89be66a](https://github.com/open-rpc/spec/commit/89be66a))
* add service description to the spec ([cd32941](https://github.com/open-rpc/spec/commit/cd32941))
* gh pages from master ([ff0d20f](https://github.com/open-rpc/spec/commit/ff0d20f)), closes [#124](https://github.com/open-rpc/spec/issues/124)
* initial commit ([508cf20](https://github.com/open-rpc/spec/commit/508cf20))
* pristine all the things ([fdf7380](https://github.com/open-rpc/spec/commit/fdf7380))
* ref oneOf throughout the spec ([824cd61](https://github.com/open-rpc/spec/commit/824cd61))
* semantic release and build ([275c10a](https://github.com/open-rpc/spec/commit/275c10a))
* use params over parameters ([ffae341](https://github.com/open-rpc/spec/commit/ffae341)), closes [#33](https://github.com/open-rpc/spec/issues/33)
