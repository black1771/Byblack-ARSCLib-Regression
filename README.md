# Byblack ARSCLib Regression

Independent regression verification for
the REAndroid/ARSCLib project.

[![Build Jar](https://github.com/black1771/Byblack-ARSCLib-Regression/actions/workflows/gradle-test.yml/badge.svg)](https://github.com/black1771/Byblack-ARSCLib-Regression/actions/workflows/gradle-test.yml)

[![Java 8 Regression](https://github.com/black1771/Byblack-ARSCLib-Regression/actions/workflows/java8-regression.yml/badge.svg)](https://github.com/black1771/Byblack-ARSCLib-Regression/actions/workflows/java8-regression.yml)

## Overview

This repository preserves a tested ARSCLib
source snapshot and regression coverage for
case-insensitive resource path collisions.

It is an independent verification project,
not an official REAndroid release.

## Verified results

| Check | Result |
|---|---|
| Local JUnit tests | 55 passed |
| Local Java 8 API compilation | Passed |
| GitHub Java 8 Regression | Passed |
| GitHub Build Jar | Passed |
| GitHub JAR artifact upload | Passed |

The Java 8 API check uses a newer JDK
with the Java compiler's `--release 8`
option. It is not a Java 8 runtime test.

## Continuous integration

Two GitHub Actions workflows are available:

- Build Jar: compiles, tests and packages
  the library.
- Java 8 Regression: validates compilation
  against Java 8 APIs and runs JUnit tests.

Both workflows run on pushes to main and
on pull requests targeting main.

## Original contribution

Original pull request:

https://github.com/REAndroid/ARSCLib/pull/110

Tested contribution commit:

`bd9dc9b0719867ffe954fc3630eeb3c0c4dfa72f`

## Test evidence

See:

`evidence/LOCAL-TEST-RESULTS.md`

The GitHub Actions history provides
independent CI execution results.

## Upstream project

https://github.com/REAndroid/ARSCLib

## License

The upstream source remains subject to
its original license. See `LICENSE`
or the upstream licensing files.
