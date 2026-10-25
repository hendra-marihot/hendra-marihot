# Hendra Marihot

Senior Mobile Engineer · Flutter and native Android · Jakarta

I build and ship mobile apps for a living, and I care most about the parts that keep an app healthy after launch: architecture that survives a growing team, offline-first data flow, measured performance, and CI that catches regressions before users do.

## Start here

If you only have ten minutes, open these three:

| Repo | What it shows |
|---|---|
| [compose-newsreader](https://github.com/hendra-marihot/compose-newsreader) | Multi-module native Android: Compose, Hilt, Room, Retrofit, offline-first with Flow-based unidirectional data flow and Gradle convention plugins |
| [flutter-expense-tracker](https://github.com/hendra-marihot/flutter-expense-tracker) | Feature-first Clean Architecture in Flutter: Riverpod 3, Drift, go_router, Material 3, with provider and repository tests |
| [compose-performance-lab](https://github.com/hendra-marihot/compose-performance-lab) | Compose performance anti-patterns and their fixes, measured with live recomposition counters and Macrobenchmark |

## Portfolio

Each repository isolates one competency. Every one has a CI pipeline, a test suite, and an Apache-2.0 license.

**Native Android (Kotlin / Jetpack Compose)**

- [compose-newsreader](https://github.com/hendra-marihot/compose-newsreader) — architecture, modularization, offline-first data
- [android-design-system](https://github.com/hendra-marihot/android-design-system) — "Flavor", a tokenized Material 3 component library with a catalog app
- [compose-performance-lab](https://github.com/hendra-marihot/compose-performance-lab) — recomposition, stability, lazy-list keys, Macrobenchmark

**Flutter (Dart)**

- [flutter-expense-tracker](https://github.com/hendra-marihot/flutter-expense-tracker) — Clean Architecture, Riverpod, Drift, go_router
- [flutter-ui-toolkit](https://github.com/hendra-marihot/flutter-ui-toolkit) — `flutter_flavor_ui`, a reusable widget package: shimmer skeletons, adaptive layouts, async buttons, validators
- [flutter-platform-bridge](https://github.com/hendra-marihot/flutter-platform-bridge) — MethodChannel and EventChannel against real Android APIs, with Pigeon and dart:ffi tradeoffs

**Cross-platform and delivery**

- [kmp-currency-converter](https://github.com/hendra-marihot/kmp-currency-converter) — Kotlin Multiplatform shared logic with Ktor and Koin, Compose Android UI, iOS XCFramework
- [mobile-ci-cd-templates](https://github.com/hendra-marihot/mobile-ci-cd-templates) — GitHub Actions, Codemagic and Fastlane templates for Android and Flutter, with BATS-tested release scripts

## How I work

- Offline-first by default: the local database is the source of truth, the network is a sync source.
- Tests sit where the risk is: ViewModels, repositories, use cases, and migrations before pixel-level UI.
- Every repo builds and tests on every push. If a green badge is not there, the work is not done.
- READMEs explain the decisions and the tradeoffs, not only the stack.

## Elsewhere

- [LinkedIn](https://www.linkedin.com/in/hendra-marihot/)
