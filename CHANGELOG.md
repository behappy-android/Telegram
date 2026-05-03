# Changelog

All notable changes to BeHappy for Android will be documented in this
file.

Changes inherited from upstream Telegram for Android are not repeated
here. This changelog covers only modifications made by the BeHappy
Android Authors.

The format is based on [Keep a Changelog](https://keepachangelog.com/),
and this project adheres to [Semantic Versioning](https://semver.org/).

## [Unreleased]

### Added
- Initial fork from upstream Telegram for Android.
- MVSy 1.0 protocol layer (replaces MTProto 2.0).
- Connection to BeHappy backend (`mvsy.behappy.rest`).
- BeHappy branding: app name, icon, splash screen, color scheme.

### Removed
- Telegram-specific branding (name, logo, About text).
- Telegram Premium UI surfaces.
- Telegram Stars integration.
- Fragment / TON wallet integration.
- Sponsored messages.
- Telegram-specific deep links (`tg://`, `t.me`).

### Changed
- Default DC list points to BeHappy servers.
- App package id renamed to `rest.behappy.android`.
- Help and support links point to BeHappy resources.

[Unreleased]: https://github.com/behappy-android/Telegram/compare/v0.0.0...HEAD
