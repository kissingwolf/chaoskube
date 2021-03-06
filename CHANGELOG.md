## v0.11.0 - 2018-10-09

  Features:
  * [#110](https://github.com/linki/chaoskube/pull/110) Add option to define grace period given to pods @palmerabollo
  * [#105](https://github.com/linki/chaoskube/pull/105) Implement event creation after terminating a pod @djboris9

  Updates:
  * [#107](https://github.com/linki/chaoskube/pull/107) Replace `glog` with a `noop` logger to allow for read-only filesystem @linki

## v0.10.0 - 2018-08-06

  Features:
  * [#97](https://github.com/linki/chaoskube/pull/97) Expose basic metrics via Prometheus @bakins
  * [#94](https://github.com/linki/chaoskube/pull/94) Add a health check endpoint @bakins
  * [#86](https://github.com/linki/chaoskube/pull/86) Add a flag to exclude Pods under a certain age @bakins
  * [#84](https://github.com/linki/chaoskube/pull/84) Exclude Pods that are not in phase `Running` @linki
  * [#60](https://github.com/linki/chaoskube/pull/60) Add a Dockerfile for building images for `ppc64le` @hchenxa

  Updates:
  * [#96](https://github.com/linki/chaoskube/pull/96) Use versioned functions of `client-go` @linki
  * [#95](https://github.com/linki/chaoskube/pull/95) Handle signals to enable more graceful shutdown @linki
  * [#89](https://github.com/linki/chaoskube/pull/89) Run `chaoskube` as `nobody` by default @bavarianbidi
  * [#77](https://github.com/linki/chaoskube/pull/77) Use [roveralls](https://github.com/lawrencewoodman/roveralls) to improve coverage results @linki
