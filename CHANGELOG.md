## [springtime-di] 0.3.0

### New

* Fallible custom constructors - they should return `Result<Type, ErrorPtr>`,
where `Type` is the type being returned previously. This also implies new entry
in `ComponentInstanceProviderError` and loosing some of its derived traits.

## [springtime-di] 0.2.1

### Fixed

* Doc fixes.