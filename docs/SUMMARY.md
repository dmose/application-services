[Application Services Rust Components](README.md)
- [Contributing](contributing.md)
  - [Building](building.md)
    - [How to use the local development autopublish flow for Fenix](howtos/locally-published-components-in-fenix.md)
    - [How to use the local development flow for Focus for iOS](howtos/locally-published-spm-in-ios.md)
    - [How to locally build JNA](howtos/locally-building-jna.md)
  - [How to test Rust Components](howtos/testing-a-rust-component.md)
    - [How to integration (smoke) test application-services](howtos/smoke-testing-app-services.md)
    - [Writing efficient tests](design/test-faster.md)
  - [Dependency management](dependency-management.md)
  - [How to add a new component](howtos/adding-a-new-component.md)
    - [How to build a new syncable component](howtos/building-a-rust-component.md)
    - [Naming Conventions](naming-conventions.md)
    - [How to convert a Rust Component to Uniffi](howtos/converting-a-component-to-uniffi.md)
    - [How to use Rust Components in Android](android-faqs.md)
  - [Logging](logging.md)
- [Architectural Decision Records](adr/README.md)
  - [ADR-0000](adr/0000-use-markdown-architectural-decision-records.md)
  - [ADR-0001](adr/0001-update-logins-api.md)
  - [ADR-0002](adr/0002-database-corruption.md)
  - [ADR-0003](adr/0003-swift-packaging.md)
  - [ADR-0004](adr/0004-early-startup-experiments.md)
- [Design](design/README.md)
  - [Megazords](design/megazords.md)
  - [Sync Manager](design/sync-manager.md)
  - [Sync overview](design/sync-overview.md)
  - [Shipping Rust Components as Swift Packages](design/swift-package-manager.md)
  - [Rust Component's Strategy](design/components-strategy.md)
  - [Metrics - (Glean Telemetry)](design/metrics.md)
  - [Rust Version Policy](design/rust-versions.md)
- [How to cut a new release](howtos/cut-a-new-release.md)
  - [CI Publishing tools and flow](build-and-publish-pipeline.md)
  - [How to upgrade NSS](howtos/upgrading-nss-guide.md)
- [Rustdocs for components](rust-docs/fxa_client/index.html)
- [Adding to these documents](adding-docs.md)