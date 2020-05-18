<div align="center">
	<p>
		<img alt="CircleCI Logo" src="https://raw.githubusercontent.com/ThoughtWorks-DPS/di-circleci-remote-docker/master/img/circle-circleci.svg?sanitize=true" width="75" />
	</p>
  <h3>feedyard orbs</h3>
  <h1>orb-tools</h1>

  <h5>an sdlc orb for authoring circleci orbs</h5>
</div>
<br />
[![feedyard]](https://circleci.com/gh/feedyard/orb-tools.svg?style=shield)] [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/feedyard/orb-tools)] 
Basically a slimmed down version of the capabilities found in CircleCI's own [orb-tools-orb](https://github.com/CircleCI-Public/orb-tools-orb).  


[![Software License]](https://img.shields.io/badge/license-MIT-blue.svg)

The differences (and motivation to take the time to create) are:

* Branch merges are not expected for team engaged in trunk based development (or TBD)
* Modifications to logic in iynere/compare-url for TBD and support for alpine-based docker image as the executor
* Modified testing model. CI testing during orb development certainly has it's own idiosyncrasies :grin:

Example private registry workflow: (see [orb registry](https://circleci.com/orbs/registry/orb/feedyard/executor-tools) for detailed examples)

See orb registry help and examples pages for use descriptions.
