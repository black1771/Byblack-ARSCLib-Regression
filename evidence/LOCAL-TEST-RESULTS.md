# Local verification results

Commit: bd9dc9b

## Standard test run

BUILD SUCCESSFUL in 15s

Tests: 55
Failures: 0
Errors: 0
Skipped: 0

## Java 8 API compilation

Gradle clean test with:

--release 8

BUILD SUCCESSFUL in 12s

Exit code: 0

## Notes

Verification was performed locally in Termux
using OpenJDK 26 and Gradle 9.6.0.

This does not establish that GitHub Actions CI
passed or that the code was run on a Java 8 JVM.
