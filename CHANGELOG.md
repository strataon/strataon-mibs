# Changelog

All notable changes to the STRATAON MIB are documented in this file.

## [1.8] - 2026-09-11

### Added

- Added support for sentiaLOK.
- Added Product ID `6`.
- Added product branch `.10.6`.
- Added support for 32 subordinate stations.
- Added node, name, communication status, firmware and device type
  information for each station.
- Added 8 digital inputs and 8 digital outputs per station.
- Added station attributes using sub-identifiers `101..132`.

## [1.7] - 2026-08-16

### Added

- Added support for sentiaPRO.
- Added Product ID `5`.
- Added product branch `.10.5`.
- Added product-specific scalar objects for temperature, humidity,
  alarm status, locks and doors.

## [1.6] - 2026-08-16

### Added

- Added support for sentiaMAN.
- Added Product ID `4`.
- Added product branch `.10.4`.
- Added support for 32 subordinate stations.
- Added station attributes using sub-identifiers `101..132`.
- Added node, name, communication status, firmware, three temperature
  measurements, humidity, alarm status, two locks and two doors for
  each station.
- Temperature and humidity values use x10 scaling.

## [1.5] - 2026-08-11

### Fixed

- Corrected environmental measurement units for miniENV.
- Defined `HUM01` and `HUM02` as `percent RH x10`.
- Defined `CO201` directly in `ppm`, without x10 scaling.
- No OIDs were changed in this release.

## [1.4] - 2026-07-31

### Added

- Consolidated the official STRATAON MIB structure.
- Added support for miniENV.

### Changed

- Standardized OIDs for miniPLC, smartPDU and miniENV.
- Standardized Count objects and channel numbering using sub-identifiers
  starting at `101`.

### Validation

- Compatibility validated with Net-SNMP.
- Compatibility validated with PRTG.
- Compatibility validated with Zabbix.

---

For detailed object definitions and OIDs, refer to the current
`STRATAON-MIB.mib` file and its internal revision history.

Copyright © 2026 STRATAON Equipamentos Eletrônicos Ltda.
