# travis-pr
Repository for output from Travis CI pull request builds.

This is needed if we want to publish output from PRs somewhere and don't want to publish plain text private key of [freemint.github.io](https://freemint.github.io).

Public part of the key is already setup as a deploy key, private part of the key is available in this repo as `pr-deploy-key`. `master` is set as a protected branch, i.e. it's impossible to wipe the whole repo out by overwriting history.

Travis CI PRs discussing this problem: https://github.com/travis-ci/travis-ci/issues/1946, https://github.com/travis-ci/travis-ci/issues/5579.
