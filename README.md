# About
This repo contains [Homebrew](https://brew.sh/) formulae.

# Installation

## Elasticsearch 1.7.6_1
`brew install "https://raw.githubusercontent.com/sevenlist/homebrew/master/elasticsearch@1.7.rb"`

Depending on if you have installed a current version of Elasticsearch via Homebrew, you need to sym link Elasticsearch 1.7 manually to be able to use it:
1. `brew unlink elasticsearch`
2. `brew link elasticsearch@1.7 --force`

Undo that using:
1. `brew unlink elasticsearch@1.7`
2. `brew link elasticsearch`

If you need more infos about the installation (e.g. file paths) type `brew info elasticsearch@1.7`.

### About the formula code
This formula was taken from the official Homebrew repository ([homebrew-core](https://github.com/Homebrew/homebrew-core/)), before it has been removed (commit [390173e](https://github.com/Homebrew/homebrew-core/commit/390173e9035a2bb4b107930c11f07d31a204ea23)) as Elasticsearch 1.7 has reached its EOL. The formula has been fixed so that it can be installed with Homebrew 1.7.7.

## OpenShift CLI 3.11
`brew install "https://raw.githubusercontent.com/sevenlist/homebrew/master/openshift-cli@3.11.rb"`

Depending on if you have installed a current version of OpenShift CLI via Homebrew, you need to sym link OpenShift CLI 3.11 manually to be able to use it:
1. `brew unlink openshift-cli`
2. `brew link openshift-cli@3.11 --force`

Undo that using:
1. `brew unlink openshift-cli@3.11`
2. `brew link openshift-cli`

If you need more infos about the installation (e.g. file paths) type `brew info openshift-cli@3.11`.

### About the formula code
This formula was taken from the official Homebrew repository ([homebrew-core](https://github.com/Homebrew/homebrew-core/)), before it has been removed (commit [1446e1f](https://github.com/Homebrew/homebrew-core/commit/1446e1f05b4d4eb76dca1efe4eff5910c133a5cf)).