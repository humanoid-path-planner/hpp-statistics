# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]

## [9.0.2] - 2026-07-24



## [9.0.0] - 2026-07-06



## [7.0.0] - 2026-03-06



## [6.1.0] - 2025-10-23



## [6.0.0] - 2024-12-07

No changes


## [5.2.0] - 2024-10-09

Changes in v5.2.0:
- nix: move package to nixpkgs
- ci: use https
- setup mergify


## [5.1.0] - 2024-07-02

Changes in v5.1.0:
- Nix: initial support
- update tooling


## [5.0.0] - 2024-03-31

Changes in v5.0.0:
- update packaging
- update tooling


## [4.15.1] - 2023-01-20



## [4.14.0] - 2022-11-02



## [4.13.0] - 2022-05-31



## [4.12.0] - 2021-10-06



## [4.11.0] - 2021-05-04

Changes in v4.11.0:
- mark constructor as default.
- deactivate travis
- sync submodule
- install package.xml

## [4.10.1] - 2020-09-24

Changes since v4.9.0:
* Add package.xml
* Handle dependencies via cmake instead of pkg-config (cmake submodule)


## [4.9.0] - 2020-04-29

Changes in v4.9.0:
- CMake Exports

## [4.8.0] - 2019-11-28

Changes since v4.5.0:
- Update CMake

## [4.5.0] - 2019-04-24



## [4.4.0] - 2019-03-19



## [4.3.0] - 2019-01-31

- [Doc] Use HPP doc from cmake module.
- [CMake] Synchronize module.


## [4.2.0] - 2018-10-11

Changes since v1.1.1:
- use HPP version scheme
- [CI] add .gitlab-ci.yml & badges

## [1.1] - 2018-03-14

* Update dependency versions.
* Add DiscreteDistribution::values()
* Add travis support
* Fix forgotten PKG_CONFIG_USE_DEPENDENCY
* Use std::size_t instead of size_t. Remove src/bin.cc in CMakeLists.txt
* Make SuccessStatistics compliant with STL container
* Fix CMakeLists
* Add SuccessStatistics::isLowRatio
* Move definition from bin.cc to bin.hh
* Move function definition to success-bin.hh
* Move src/success-bin.cc -> include/hpp/statistics/success-bin.hxx
* Add Statistics::clear
* Fix compilation warnings
* Update submodule link
* Add Statistics::numberOfBins
* Fix compilation warnings in 64bit.
* fix warning errors on 64bits unsigned int conversion


[Unreleased]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v9.0.2...HEAD
[9.0.2]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v9.0.0...v9.0.2
[9.0.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v7.0.0...v9.0.0
[7.0.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v6.1.0...v7.0.0
[6.1.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v6.0.0...v6.1.0
[6.0.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v5.2.0...v6.0.0
[5.2.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v5.1.0...v5.2.0
[5.1.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v5.0.0...v5.1.0
[5.0.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.15.1...v5.0.0
[4.15.1]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.14.0...v4.15.1
[4.14.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.13.0...v4.14.0
[4.13.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.12.0...v4.13.0
[4.12.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.11.0...v4.12.0
[4.11.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.10.1...v4.11.0
[4.10.1]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.9.0...v4.10.1
[4.9.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.8.0...v4.9.0
[4.8.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.5.0...v4.8.0
[4.5.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.4.0...v4.5.0
[4.4.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.3.0...v4.4.0
[4.3.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v4.2.0...v4.3.0
[4.2.0]: https://github.com/humanoid-path-planner/hpp-statistics/compare/v1.1...v4.2.0
[1.1]: https://github.com/humanoid-path-planner/hpp-statistics/releases/tag/v1.1
