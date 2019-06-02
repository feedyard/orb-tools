# orb-tools [![CircleCI status](https://circleci.com/gh/feedyard/orb-tools.svg "CircleCI status")](https://circleci.com/gh/feedyard/orb-tools-orb) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/feedyard/orb-tools)](https://circleci.com/orbs/registry/orb/feedyard/orb-tools) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/feedyard/orb-tools/master/LICENSE)

An orb for authoring orbs.

Basically a slimmed down version of the capabilities found in CircleCI's own [orb-tools-orb](https://github.com/CircleCI-Public/orb-tools-orb).

The differences (and motivation to take the time to create) are:

* For team engaged in TBD or trunk based development, where branch merges are not expected
* Modifications to logic in iynere/compare-url for both TBD and support for alpine-based docker image as the executor
* Modified testing model. CI testing during orb development certainly has it's own idiosyncrasies :grin:

See orb registry help and examples pages for use descriptions.

