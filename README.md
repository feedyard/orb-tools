<div align="center">
  <h3>DEPRECATED. Orb moved to [twdps/orb-tools](https://github.com/ThoughtWorks-DPS/orb-tools). See repo or orb-registry for additional details.</h3>
  <h3>feedyard orbs</h3>
  <h1>orb-tools</h1>
  <a href="https://app.circleci.com/pipelines/github/feedyard/orb-tools"><img src="https://circleci.com/gh/feedyard/orb-tools.svg?style=shield"></a> 
  <h5>an sdlc orb for authoring circleci orbs</h5>
</div>
<br />

Basically a slimmed down version of the capabilities found in CircleCI's own [orb-tools-orb](https://github.com/CircleCI-Public/orb-tools-orb).  

The differences (and motivation to take the time to create) are:

* Branch merges are not expected for team engaged in trunk based development (or TBD)
* Modifications to logic in iynere/compare-url for TBD and support for alpine-based docker image as the executor
* Modified testing model. CI testing during orb development certainly has it's own idiosyncrasies :grin:

Example private registry workflow: (see [orb registry](https://circleci.com/orbs/registry/orb/feedyard/orb-tools) for detailed examples)

See orb registry help and examples pages for use descriptions.



