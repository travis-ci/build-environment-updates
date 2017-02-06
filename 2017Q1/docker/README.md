# promotion report

## precise stacks

- [travis cookbooks diff](https://github.com/travis-ci/travis-cookbooks/compare/a68419e...479d954)

### Added
- preinstalled postgresql 9.5
- preinstalled python 3.5
- preinstall `wheel` in each preinstalled python prior to package installation

### Changed
- bison `2.4.1` :arrow_right: `3.0.4`
- firefox `31.0esr` :arrow_right: `38.4.0esr`
- gimme `0.2.2` :arrow_right: `1.0.0`
- preinstalled php versions bumped to more recent point releases
- preinstalled python versions bumped to more recent point releases
- updated phpbuild
- updated pyenv
- updated sbt-extras
- postgis `2.1` :arrow_right: `2.2`
- rabbitmq (debian testing) :arrow_right: `3.4.3`
- rvm `1.26.8` :arrow_right: `1.26.10`

### Removed
- codehaus.org maven repo

### Security
- all system package updates

## trusty stacks

- [travis cookbooks diff](https://github.com/travis-ci/travis-cookbooks/compare/58fad1f...9ac3e46)

### Added
- rebar3
- shellcheck `0.4.5`
- shfmt `1.0.0`
- yarn `0.17.8`
- couchdb
- elasticsearch
- riak

### Changed
- elasticsearch :arrow_right: `5.0.2`
- firefox :arrow_right: `50.0.2`
- gradle :arrow_right: `3.2.1`
- updated lein
- maven :arrow_right: `3.3.9`
- updated mercurial
- updated cassandra
- updated git
- updated rabbitmq
- docker :arrow_right: `1.12.6`
- preinstalled python versions bumped to more recent point releases

### Removed
- preinstalled golang libraries for some versions

### Security
- all system package updates
