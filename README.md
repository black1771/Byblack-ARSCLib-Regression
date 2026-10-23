# Byblack ARSCLib Regression

Independent regression testing and verification
for REAndroid/ARSCLib.

## Original contribution

Original pull request:
https://github.com/REAndroid/ARSCLib/pull/110

Verified commit:
`bd9dc9b0719867ffe954fc3630eeb3c0c4dfa72f`

## Regression coverage

Case-insensitive Android resource path collisions.

Test:
`PathSanitizerCaseInsensitiveTest`

## Local verification

Environment:

- Android / Termux aarch64
- OpenJDK 26.0.2
- Gradle 9.6.0
- Java 8 compilation target

Results:

- 55 tests executed
- 55 passed
- 0 failures
- 0 errors
- 0 skipped
- Java 8 bytecode version 52
- Clean build and tests with `--release 8`: successful

These are local verification results, not
GitHub Actions CI results.

## Upstream

This project contains a snapshot of ARSCLib
at the tested contribution commit.

Original project:
https://github.com/REAndroid/ARSCLib

This repository is an independent test snapshot,
not an official REAndroid release.

## License

See the upstream LICENSE file.
