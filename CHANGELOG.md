# Changelog

## [1.0.2](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v1.0.1...v1.0.2) (2021-05-24)


### Bug Fixes

* **latest.sls:** remove old apt repository following bintray shutdown ([2fbd40f](https://github.com/saltstack-formulas/rabbitmq-formula/commit/2fbd40f443ff96b0619b5256793d0d0f03a9d03a))

## [1.0.1](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v1.0.0...v1.0.1) (2021-05-21)


### Bug Fixes

* **user:** fix rendering error for user; fix ci ([346df02](https://github.com/saltstack-formulas/rabbitmq-formula/commit/346df024ce6a4afaf67f96ffd82021121de385ad))


### Continuous Integration

* add `arch-master` to matrix and update `.travis.yml` [skip ci] ([d46cd1d](https://github.com/saltstack-formulas/rabbitmq-formula/commit/d46cd1d40a108caec3fb849c9db00e9501e4a84c))
* **kitchen+gitlab:** adjust matrix to add `3003` [skip ci] ([887ed24](https://github.com/saltstack-formulas/rabbitmq-formula/commit/887ed24bfce8a0638233280a9fcfaebfe06043aa))


### Documentation

* **map.jinja:** fix `rst-lint` violation [skip ci] ([93dd429](https://github.com/saltstack-formulas/rabbitmq-formula/commit/93dd429e19ebbe28ea152c78c97428e4a9e2c17c))
* remove files which aren't formula-specific [skip ci] ([0122a74](https://github.com/saltstack-formulas/rabbitmq-formula/commit/0122a74653229c952665a497beac5b1bcc6634dc))


### Tests

* **_mapdata:** add verification file for `fedora-34` [skip ci] ([ede918c](https://github.com/saltstack-formulas/rabbitmq-formula/commit/ede918cd0bc0f19dc333395e1be4054e5c765968))
* **_mapdata:** generate updated `map.jinja` verification files ([ab297a5](https://github.com/saltstack-formulas/rabbitmq-formula/commit/ab297a569e292fe09d0086ebfef2d455e3d71bd7))
* **pillar:** remove unused test pillar files ([8f21f49](https://github.com/saltstack-formulas/rabbitmq-formula/commit/8f21f49488a11f8d7a5bb295b3db8aeb052c343f))

# [1.0.0](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.20.4...v1.0.0) (2021-04-20)


### Bug Fixes

* **centos:** get service running to work ([ad5636a](https://github.com/saltstack-formulas/rabbitmq-formula/commit/ad5636ad17447b84b28e3d4fd4fb7145da83052b))
* **centos:** get systemd service passing ([ee01836](https://github.com/saltstack-formulas/rabbitmq-formula/commit/ee0183684e5a36846d59e7880e48ddf27d8476c3))


### Code Refactoring

* **formula:** align to template formula ([d55402f](https://github.com/saltstack-formulas/rabbitmq-formula/commit/d55402f0b87889b9a47bd289148232de106302a4))


### BREAKING CHANGES

* **formula:** This formula has been refactored to align with
template formula. States have changed, and some pillar data

## [0.20.4](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.20.3...v0.20.4) (2021-04-12)


### Bug Fixes

* **latest.sls:** change apt repository following bintray shutdown ([ac16a5f](https://github.com/saltstack-formulas/rabbitmq-formula/commit/ac16a5f3e08f539d944ea5ecf3de523a5c796301))


### Continuous Integration

* **gemfile+lock:** use `ssf` customised `kitchen-docker` repo [skip ci] ([c456f53](https://github.com/saltstack-formulas/rabbitmq-formula/commit/c456f53235f12bfa7698b4462e6ddc39e79e3c1e))
* **kitchen+ci:** use latest pre-salted images (after CVE) [skip ci] ([9a6f0c6](https://github.com/saltstack-formulas/rabbitmq-formula/commit/9a6f0c6e5bcd8bf0b13b8b02f256a8f1e763109e))
* **kitchen+gitlab-ci:** use latest pre-salted images [skip ci] ([ebb55f3](https://github.com/saltstack-formulas/rabbitmq-formula/commit/ebb55f3aec4dedc56315e83f707a3144700bd3d1))
* **pre-commit:** update hook for `rubocop` [skip ci] ([04ddd76](https://github.com/saltstack-formulas/rabbitmq-formula/commit/04ddd762bc7e17820401694f0605d1238e7753a7))


### Tests

* standardise use of `share` suite & `_mapdata` state [skip ci] ([2d82763](https://github.com/saltstack-formulas/rabbitmq-formula/commit/2d8276361caf62a89a4e40e18de8e0f783a6d917))
* **_mapdata:** add verification files for Fedora 32+33 & Ubuntu 20.04 ([f0b0182](https://github.com/saltstack-formulas/rabbitmq-formula/commit/f0b0182b2697a08ab4928037a3fcb1c8be40cf17))
* **share:** standardise with latest changes [skip ci] ([133ba1d](https://github.com/saltstack-formulas/rabbitmq-formula/commit/133ba1dee12c1d71ca12e3f7c6c4b6285a8fc07b))

## [0.20.3](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.20.2...v0.20.3) (2021-01-14)


### Bug Fixes

* **_mapdata:** ensure map data is directly under `values` ([164fb62](https://github.com/saltstack-formulas/rabbitmq-formula/commit/164fb6263f4e741b574741e39801549b7837fdc8))


### Tests

* **_mapdata:** update for `_mapdata/init.sls` change ([dbadb4e](https://github.com/saltstack-formulas/rabbitmq-formula/commit/dbadb4e89d651cfef5ffa4a62e2a9b717f9ea38c))

## [0.20.2](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.20.1...v0.20.2) (2020-12-23)


### Code Refactoring

* **map:** use top-level `values:` key in `map.jinja` dumps ([7cff4de](https://github.com/saltstack-formulas/rabbitmq-formula/commit/7cff4deae2177073bb325bcf9eeb88919f705fc5))

## [0.20.1](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.20.0...v0.20.1) (2020-12-22)


### Continuous Integration

* **commitlint:** ensure `upstream/master` uses main repo URL [skip ci] ([af49850](https://github.com/saltstack-formulas/rabbitmq-formula/commit/af49850d605468ec956c22895f92fe8084dac7c3))
* **gitlab-ci:** add `rubocop` linter (with `allow_failure`) [skip ci] ([4d549db](https://github.com/saltstack-formulas/rabbitmq-formula/commit/4d549db99d23f76b0922d0b98c9ad2d41dab8641))


### Tests

* **_mapdata:** generate verification files ([2b9a968](https://github.com/saltstack-formulas/rabbitmq-formula/commit/2b9a968fb64a32c2d179e260e598f72f9c6e413b))
* **map:** verify `map.jinja` dump using `_mapdata` state ([4d0287d](https://github.com/saltstack-formulas/rabbitmq-formula/commit/4d0287d2849c09507944b95e8c86c3043273a785))

# [0.20.0](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.19.1...v0.20.0) (2020-12-16)


### Continuous Integration

* **gemfile.lock:** add to repo with updated `Gemfile` [skip ci] ([5e215cd](https://github.com/saltstack-formulas/rabbitmq-formula/commit/5e215cd5df50402875ee7ea92de7677b62029b71))
* **gitlab-ci:** use GitLab CI as Travis CI replacement ([9ac7690](https://github.com/saltstack-formulas/rabbitmq-formula/commit/9ac76908833c7615cc2cd82cc7110c356673d171))
* **kitchen:** use `saltimages` Docker Hub where available [skip ci] ([fcdef3f](https://github.com/saltstack-formulas/rabbitmq-formula/commit/fcdef3ff327385b8cde4aae17cbd47514e761f4c))
* **kitchen+travis:** remove `master-py2-arch-base-latest` [skip ci] ([d4a6c8f](https://github.com/saltstack-formulas/rabbitmq-formula/commit/d4a6c8fadf3f8dacce099c7ae27194cfddba7fa5))
* **pre-commit:** add to formula [skip ci] ([2547b23](https://github.com/saltstack-formulas/rabbitmq-formula/commit/2547b23f55fd3927c5df12296a459584f4cae693))
* **pre-commit:** enable/disable `rstcheck` as relevant [skip ci] ([f04bfe6](https://github.com/saltstack-formulas/rabbitmq-formula/commit/f04bfe6f57d1c039d81c838b94db26b14f8549fe))
* **pre-commit:** finalise `rstcheck` configuration [skip ci] ([3e1b397](https://github.com/saltstack-formulas/rabbitmq-formula/commit/3e1b39778f4ff95b918cf571290ef18a4402e405))
* **travis:** add notifications => zulip [skip ci] ([232e38f](https://github.com/saltstack-formulas/rabbitmq-formula/commit/232e38fb5c561b29608d542b97991de6406d5e52))
* **workflows/commitlint:** add to repo [skip ci] ([cea9af8](https://github.com/saltstack-formulas/rabbitmq-formula/commit/cea9af8f419144a50f3cc5d83c9307d1c4018b92))


### Features

* **suse:** basic suse support ([4a67836](https://github.com/saltstack-formulas/rabbitmq-formula/commit/4a67836fa02bec3efda06d2affae7f4940cad953))

## [0.19.1](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.19.0...v0.19.1) (2020-02-18)


### Bug Fixes

* **slspath:** use `tplroot` to prevent path errors in `Neon` ([d4982df](https://github.com/saltstack-formulas/rabbitmq-formula/commit/d4982df5c573fd3cc91177f56ad914f6916f02b4)), closes [/travis-ci.org/myii/rabbitmq-formula/jobs/651200625#L1830](https://github.com//travis-ci.org/myii/rabbitmq-formula/jobs/651200625/issues/L1830) [/travis-ci.org/myii/rabbitmq-formula/jobs/651200626#L1779](https://github.com//travis-ci.org/myii/rabbitmq-formula/jobs/651200626/issues/L1779)


### Continuous Integration

* **kitchen:** avoid using bootstrap for `master` instances [skip ci] ([e3c9993](https://github.com/saltstack-formulas/rabbitmq-formula/commit/e3c9993e8631ac5f188dbde91b609d3d5aa12167))
* **kitchen:** standardise structure [skip ci] ([977c8a0](https://github.com/saltstack-formulas/rabbitmq-formula/commit/977c8a02bbfcb8a6995fe54188481d3f9b02c4eb))

# [0.19.0](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.18.0...v0.19.0) (2019-12-23)


### Continuous Integration

* **kitchen:** add salt state to kitchen exec ([85e2e32](https://github.com/saltstack-formulas/rabbitmq-formula/commit/85e2e321c6c179f6eefdea226e64b2a1d4888028))
* **kitchen:** standardise structure [skip ci] ([3eaab51](https://github.com/saltstack-formulas/rabbitmq-formula/commit/3eaab517a098ed2b9c27b1f996ac72b2293d92c7))
* **travis:** use `major.minor` for `semantic-release` version [skip ci] ([2e6a92b](https://github.com/saltstack-formulas/rabbitmq-formula/commit/2e6a92becc13e421320b4963bdd4a45302bbc5dd))


### Features

* config state now also managed rabbitmq env file ([53f12d2](https://github.com/saltstack-formulas/rabbitmq-formula/commit/53f12d2f8053c0a4afe3f8fc3ef5006e453cc435))


### Tests

* **inspec:** test new rabbitmq-env file ([f7e5d39](https://github.com/saltstack-formulas/rabbitmq-formula/commit/f7e5d391d7537fe91a0b425043b7d83bfb247511))

# [0.18.0](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.17.0...v0.18.0) (2019-12-19)


### Continuous Integration

* **gemfile:** restrict `train` gem version until upstream fix [skip ci] ([e97c976](https://github.com/saltstack-formulas/rabbitmq-formula/commit/e97c976c4b3f3c38ff05886787289ca191912e73))
* **travis:** quote pathspecs used with `git ls-files` [skip ci] ([b350c17](https://github.com/saltstack-formulas/rabbitmq-formula/commit/b350c1704af7d624b2b975552a6ff01bac6b3aac))
* **travis:** run `shellcheck` during lint job [skip ci] ([b50083a](https://github.com/saltstack-formulas/rabbitmq-formula/commit/b50083a1f0b9489fade69da6027e00767ebd5225))


### Features

* config_files source can be a salt:// path ([69308a0](https://github.com/saltstack-formulas/rabbitmq-formula/commit/69308a071089e75d26915c0cd7e9e7aef7a9976a))


### Tests

* add test for config_files ([2854d1b](https://github.com/saltstack-formulas/rabbitmq-formula/commit/2854d1bc112349f7344c153430c0c401e8654344))

# [0.17.0](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.16.0...v0.17.0) (2019-11-21)


### Continuous Integration

* **travis:** opt-in to `dpl v2` to complete build config validation [skip ci] ([ff04ee9](https://github.com/saltstack-formulas/rabbitmq-formula/commit/ff04ee9439d4884a5ced793ee978e056064908a8))


### Features

* **config.sls:** remove guest user by default ([4531ac4](https://github.com/saltstack-formulas/rabbitmq-formula/commit/4531ac48983f9ad7da51f4d6b562754483d9baad))


### Tests

* **rabbitmq_users_spec.rb:** fix rubocop violations ([57efa45](https://github.com/saltstack-formulas/rabbitmq-formula/commit/57efa458af19851ae030eb788f35fcf20bb157b6))

# [0.16.0](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.15.1...v0.16.0) (2019-11-19)


### Bug Fixes

* **latest:** ensure required Debian packages are installed ([89b470f](https://github.com/saltstack-formulas/rabbitmq-formula/commit/89b470f7124795353a5087ac872d1e8c510f240c))


### Continuous Integration

* **kitchen+travis:** add `latest` suite ([29fbcd2](https://github.com/saltstack-formulas/rabbitmq-formula/commit/29fbcd2f374bfd02742743587cda6bbcbe6389c7))
* **travis:** apply changes from build config validation [skip ci] ([4a1dacb](https://github.com/saltstack-formulas/rabbitmq-formula/commit/4a1dacbff36199c3692336fe6ac2a29ceaae49a8))


### Features

* **travis:** apply changes from build config validation ([7d9533c](https://github.com/saltstack-formulas/rabbitmq-formula/commit/7d9533c31842f36b943e033bce6b9bc794121d1d))

## [0.15.1](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.15.0...v0.15.1) (2019-11-14)


### Bug Fixes

* **latest.sls:** use Bintray repo on Debian ([b50f347](https://github.com/saltstack-formulas/rabbitmq-formula/commit/b50f347c94d582f43d86182959a8b966e78dac0e))
* **release.config.js:** use full commit hash in commit link [skip ci] ([b4b27d2](https://github.com/saltstack-formulas/rabbitmq-formula/commit/b4b27d2479770312e5130692dfa44c003857be1d))


### Continuous Integration

* **kitchen:** use `develop` image until `master` is ready (`amazonlinux`) [skip ci] ([a5a1944](https://github.com/saltstack-formulas/rabbitmq-formula/commit/a5a194408e7f81a79b51be47feced1b883690753))
* **travis:** use build config validation (beta) [skip ci] ([e0f5076](https://github.com/saltstack-formulas/rabbitmq-formula/commit/e0f50762fa01b2ef3e0621dd4b4246d1d8d81e05))


### Performance Improvements

* **travis:** improve `salt-lint` invocation [skip ci] ([1bf9e23](https://github.com/saltstack-formulas/rabbitmq-formula/commit/1bf9e23f02801179b97021fe94c2d90a37d7cb04))

# [0.15.0](https://github.com/saltstack-formulas/rabbitmq-formula/compare/v0.14.1...v0.15.0) (2019-10-29)


### Features

* **semantic-release:** implement for this formula ([](https://github.com/saltstack-formulas/rabbitmq-formula/commit/2b5e400))


### Tests

* implement test using Kitchen and Inspec, and CI with Travis ([](https://github.com/saltstack-formulas/rabbitmq-formula/commit/e9eb8ff))
