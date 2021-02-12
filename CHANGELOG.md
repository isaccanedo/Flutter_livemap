# Changelog

# 0.6.0

Update dependencies

## 0.5.0

Refactor using the Fluxmap package. **Breaking changes** in `Livemap` class intialization:
- Remove `MapOptions` parameter
- Add `center` parameter
- Add `zoom` parameter
- `TileLayer` is now optional, defaulting to Open street maps

## 0.4.0

**Breaking changes**:

- Fix the `tileLayer` parameter name
- Remove the `mapController` argument for `LiveMap`

Features:

- Add a tile layers runtime switching option
- Composable sidebars

## 0.3.2

- Update dependencies
- Add map autorotation from bearing option

## 0.3.1

Update map_controller dependency

## 0.3.0

- Update dependencies
- Add support for polygons
- Move the map controller api to an external package
- Use pedantic for analysis options

## 0.2.0

- Upgrade to Android X
- Add support for lines
- Stream state changes from gestures in changefeed
- Make the marker controller methods async
- Use more strict linting rules
- Update dependencies

## 0.1.0

Initial release
