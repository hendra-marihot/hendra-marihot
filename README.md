# Hendra Marihot

Senior Mobile Engineer. Flutter and native Android. Jakarta.

I build and ship mobile apps. I care most about what keeps an app healthy after launch: architecture that survives a growing team, offline-first data, measured performance, and CI that catches regressions before users do.

## Start here

Three repos, ten minutes:

| Repo | Shows |
|---|---|
| [compose-newsreader](https://github.com/hendra-marihot/compose-newsreader) | Multi-module native Android. Compose, Hilt, Room, offline-first, one-way data flow, Gradle convention plugins |
| [flutter-expense-tracker](https://github.com/hendra-marihot/flutter-expense-tracker) | Feature-first Clean Architecture in Flutter. Riverpod 3, Drift, go_router, Material 3, tested providers and repositories |
| [compose-performance-lab](https://github.com/hendra-marihot/compose-performance-lab) | Compose performance mistakes and fixes, measured with live recomposition counters and Macrobenchmark |

## All repos

Each one covers one area. Every one has CI, tests and an Apache-2.0 license.

**Native Android**

- [compose-newsreader](https://github.com/hendra-marihot/compose-newsreader): architecture, modularization, offline-first data
- [android-design-system](https://github.com/hendra-marihot/android-design-system): Flavor, a tokenized Material 3 component library with a catalog app
- [compose-performance-lab](https://github.com/hendra-marihot/compose-performance-lab): recomposition, stability, lazy-list keys, Macrobenchmark

**Flutter**

- [flutter-expense-tracker](https://github.com/hendra-marihot/flutter-expense-tracker): Clean Architecture, Riverpod, Drift, go_router
- [flutter-ui-toolkit](https://github.com/hendra-marihot/flutter-ui-toolkit): `flutter_flavor_ui`, a widget package with shimmer skeletons, adaptive layouts, async buttons and validators
- [flutter-platform-bridge](https://github.com/hendra-marihot/flutter-platform-bridge): MethodChannel and EventChannel against real Android APIs, with Pigeon and dart:ffi tradeoffs

**Cross-platform and delivery**

- [kmp-currency-converter](https://github.com/hendra-marihot/kmp-currency-converter): Kotlin Multiplatform shared logic with Ktor and Koin, Compose UI, iOS XCFramework
- [mobile-ci-cd-templates](https://github.com/hendra-marihot/mobile-ci-cd-templates): GitHub Actions, Codemagic and Fastlane templates for Android and Flutter, with BATS-tested scripts

## How I work

- Offline-first by default. The local database is the source of truth. The network syncs it.
- Tests go where the risk is: ViewModels, repositories, use cases and migrations before pixel-level UI.
- Every repo builds and tests on every push. No green badge, not done.
- READMEs explain the decisions and the tradeoffs, not only the stack.

## Elsewhere

- [LinkedIn](https://www.linkedin.com/in/hendra-marihot/)
