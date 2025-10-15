# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.19.2](https://github.com/byteit101/deku/compare/deku_derive-v0.19.1...deku_derive-v0.19.2) - 2025-10-15

### Other

- Improve error message for id_type and missing repr ([#596](https://github.com/byteit101/deku/pull/596))
- Expose `alloc` as a selectable feature ([#582](https://github.com/byteit101/deku/pull/582))
- Fix DekuRead for #[repr(...)] enums constructed using `id` via `ctx` and whose variants assign discriminant values  ([#577](https://github.com/byteit101/deku/pull/577))
- deku_read: Use checked slice for remaining data ([#581](https://github.com/byteit101/deku/pull/581))
