# Realm KMM Sample

A _Kotlin (KMM) Project_ showing usage of Realm Kotlin in a shared module of a
multiplatform project for both Android and iOS.

The example is based on the Kotlin Multiplatform Mobile Project from
https://github.com/Kotlin/kmm-sample/blob/master/README.md

## Requirements

- JDK 11
- Android Studio [Dolphin (2021.3.1)](https://developer.android.com/studio)

## Overview

The Realm Kotlin Multiplatform SDK is used to provide a common implementation of an
`ExpressionRepository` for storing a computation history of calculations performed in the respective
apps. The repository is implemented once in the `commonMain` source set of the `shared`-module and
is triggered by the shared `Calculator`-implementation from the original KMM-sample project.

## References

For instructions on developing Kotlin Multiplatform Mobile Project, visit
[Kotlin Multiplatform Mobile Developer Portal](https://kotlinlang.org/lp/mobile/).
