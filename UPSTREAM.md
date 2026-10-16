# Local work on top of upstream

This fork (`eejd/rs-ccometix-line`, formerly `eejd/rust-ccometix-line`) has `Haleclipse/CCometixLine`
as its primary upstream. `local` is upstream release v1.1.2 (identical to upstream `master`) plus the
work below; port `ccometixline-local` in `eejd/macports-ports-local` builds the tags
`v<base>-local<NN>`. `master` is a fast-forward mirror of upstream `master`; the pre-mirror tip is archived as tag
`archive/main-pre-sync-1e747ca`.

| Change | Origin | Upstream status |
|---|---|---|
| Native stdin data + width-responsive context segment (`feat/context-native-responsive`) | local | not submitted (eejd/rs-ccometix-line issues #3-#5, #7) |
| Full native stdin schema for `InputData` (`feat/native-stdin-schema`) | local | not submitted |
| Native `rate_limits` primary path, Extra-Usage / burn-rate (`feat/usage-native-rate-limits`) | local | not submitted |
| Options editor + StyleMode selector (`feat/options-editor`) | local | not submitted |
| MSRV (`rust-version`) + CI MSRV leg (#2), `cargo fmt`, clippy fixes | local | not applicable |
