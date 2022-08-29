# Changelog

## [0.4.1] - 2020-02-27
### Added
- `map_with_owner` (#51)

### Changed
- Use dyn for trait objects (#53)

## [0.5.0] - 2022-08-29

### Changed
- Fix unsoundness problem
  - Change `map_with_owner` to safe
  - Deprecate old `map_with_owner` (Rename to `map_with_owner_direct`)
- Fix clippy warnings
