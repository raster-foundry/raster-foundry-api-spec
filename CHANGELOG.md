# Change Log

## [Unreleased](https://github.com/raster-foundry/raster-foundry/tree/develop)

### Added

- Added the `analysisId` query param to endpoints that require authorization via analyses [\#73](https://github.com/raster-foundry/raster-foundry-api-spec/pull/73)
- Added an optional `defaultLayerId` field to `Project` data model [\#78](https://github.com/raster-foundry/raster-foundry-api-spec/pull/78)
- Added spec for project layer mosaic definition and scene order [\#82](https://github.com/raster-foundry/raster-foundry-api-spec/pull/82)
- Added spec for a QP in annotation shapefile export endpoint [\#84](https://github.com/raster-foundry/raster-foundry-api-spec/pull/84)
- Added spec for layer annotation related endpoints [\#85](https://github.com/raster-foundry/raster-foundry-api-spec/pull/85)
- Added project layer ID and changed tool -> template in list endpoint for tool runs [\#83](https://github.com/raster-foundry/raster-foundry-api-spec/pull/83)
- Added project layer stats endpoint [\#88](https://github.com/raster-foundry/raster-foundry-api-spec/pull/88)
- Added project analyses endpoint [\#89](https://github.com/raster-foundry/raster-foundry-api-spec/pull/89)
- Added spec for layer ID QP on export list endpoint [\#90](https://github.com/raster-foundry/raster-foundry-api-spec/pull/90)
- Added query parameter for whether templates can sensibly be run with a single project layer [\#92](https://github.com/raster-foundry/raster-foundry-api-spec/pull/92)
- Added single band options to project layers [\#93](https://github.com/raster-foundry/raster-foundry-api-spec/pull/93)
- Added query parameter for filtering layer shape [\#94](https://github.com/raster-foundry/raster-foundry-api-spec/pull/94)
- Add split layer endpoint and datamodels [\#95](https://github.com/raster-foundry/raster-foundry-api-spec/pull/95)
- Added layerId parameter to api/scenes, clarified existing project params [\#87](https://github.com/raster-foundry/raster-foundry-api-spec/pull/87)

### Changed
- Change owner qp to array type [/#91](https://github.com/raster-foundry/raster-foundry-api-spec/pull/91)
- Updated spec for feed, removed tool-tags and categories endpoints, and updated tools and tool-runs [/#97](https://github.com/raster-foundry/raster-foundry-api-spec/pull/97)
- Added mapToken query parameter to /projects/{} and /tool-runs/ [#96](https://github.com/raster-foundry/raster-foundry-api-spec/pull/96)

### Deprecated

### Removed

### Fixed

### Security

## [1.17.0](https://github.com/raster-foundry/raster-foundry/tree/1.16.0) (2019-02-04)

### Added

- Added the `analysisId` query param to endpoints that require authorization via analyses [\#73](https://github.com/raster-foundry/raster-foundry-api-spec/pull/73)
- Added an optional `defaultLayerId` field to `Project` data model [\#78](https://github.com/raster-foundry/raster-foundry-api-spec/pull/78)
- Added spec for project layer mosaic definition and scene order [\#82](https://github.com/raster-foundry/raster-foundry-api-spec/pull/82)
- Added spec for a QP in annotation shapefile export endpoint [\#84](https://github.com/raster-foundry/raster-foundry-api-spec/pull/84)

### Fixed
- Audited Scene api spec and updated spec to reflect current endpoints [\#76](https://github.com/raster-foundry/raster-foundry-api-spec/pull/76), [\#80](https://github.com/raster-foundry/raster-foundry-api-spec/pull/80)
- Included required image fields in image properties [\#79](https://github.com/raster-foundry/raster-foundry-api-spec/pull/79)


## [1.16.0](https://github.com/raster-foundry/raster-foundry/tree/1.16.0) (2019-01-03)

### Changed

- Changed the response data model of `/users/me/roles` endpoint [\#70](https://github.com/raster-foundry/raster-foundry-api-spec/pull/70) & [\#72](https://github.com/raster-foundry/raster-foundry-api-spec/pull/72)

## [1.15.0](https://github.com/raster-foundry/raster-foundry/tree/1.15.0) (2018-11-30)

### Added

- Created tile server spec [\#61](https://github.com/raster-foundry/raster-foundry-api-spec/pull/61)

### Changed

- Publish spec YAML file to version prefixed directory [\#60](https://github.com/raster-foundry/raster-foundry-api-spec/pull/60)

### Fixed

- Audit and fix some project related endpoints [\#66](https://github.com/raster-foundry/raster-foundry-api-spec/pull/66), [\#69](https://github.com/raster-foundry/raster-foundry-api-spec/pull/69)

## [1.13.1](https://github.com/raster-foundry/raster-foundry/tree/1.13.1) (2018-10-23)

### Removed

- Remove /order GET from /projects/{} since it doesn't exist [\#56](https://github.com/raster-foundry/raster-foundry-api-spec/pull/56)

## [1.13.0](https://github.com/raster-foundry/raster-foundry/tree/1.13.0) (2018-10-30)

### Added

- Added ownershipType, groupType, and groupId filters [\#55](https://github.com/raster-foundry/raster-foundry-api-spec/pull/55/)

### Changed

- Switched to [keepachangelog](https://keepachangelog.com/en/1.0.0/) CHANGELOG format [\#52](https://github.com/raster-foundry/raster-foundry-api-spec/pull/52)

### Removed

- Outdated text referencing inability for users to create datasources [\#55](https://github.com/raster-foundry/raster-foundry-api-spec/pull/55/)
- nonexistent organization list endpoint [\#55](https://github.com/raster-foundry/raster-foundry-api-spec/pull/55/)

## [1.11.0](https://github.com/raster-foundry/raster-foundry-api-spec/tree/1.11.0) (2018-09-05)

[Full Changelog](https://github.com/raster-foundry/raster-foundry-api-spec/compare/1.5.0...1.11.0)

**Merged pull requests:**

- Replace generic params with sensible names in routes [\#47](https://github.com/raster-foundry/raster-foundry-api-spec/pull/47)
- Update users/me endpoint specs [\#45](https://github.com/raster-foundry/raster-foundry-api-spec/pull/45)
- Update responses for adding scenes to projects [\#44](https://github.com/raster-foundry/raster-foundry-api-spec/pull/44)

## [1.5.0](https://github.com/raster-foundry/raster-foundry-api-spec/tree/1.5.0) (2018-09-05)

[Full Changelog](https://github.com/raster-foundry/raster-foundry-api-spec/compare/1.4.0...1.5.0)

**Merged pull requests:**

- Use shapes for AOIs raster-foundry/raster-foundry\#3756 [\#38](https://github.com/raster-foundry/raster-foundry-api-spec/pull/38)
- Add thumbnail query parameters [\#36](https://github.com/raster-foundry/raster-foundry-api-spec/pull/36)
- Remove defunct team routes [\#35](https://github.com/raster-foundry/raster-foundry-api-spec/pull/35)
- Add annotation group urls and update annotation object definition [\#34](https://github.com/raster-foundry/raster-foundry-api-spec/pull/34)

## [1.4.0](https://github.com/raster-foundry/raster-foundry-api-spec/tree/1.4.0) (2018-07-05)

[Full Changelog](https://github.com/raster-foundry/raster-foundry-api-spec/compare/c206ed6568dd32fd6ce3377eeeefdfd803351079...1.4.0)

**Merged pull requests:**

- Deploy to staging bucket in CI when merging to develop [\#32](https://github.com/raster-foundry/raster-foundry-api-spec/pull/32)
- Add scenes thumbnail endpoint [\#31](https://github.com/raster-foundry/raster-foundry-api-spec/pull/31)
- Add bands to DatasourceThin [\#30](https://github.com/raster-foundry/raster-foundry-api-spec/pull/30)
- Add annotation shapefile routes [\#27](https://github.com/raster-foundry/raster-foundry-api-spec/pull/27)
- Add tests and setup Travis CI [\#26](https://github.com/raster-foundry/raster-foundry-api-spec/pull/26)
- Features/lk/update platform org user routes [\#25](https://github.com/raster-foundry/raster-foundry-api-spec/pull/25)
- Updates for Organizations [\#24](https://github.com/raster-foundry/raster-foundry-api-spec/pull/24)
- Add UserThin definition and use in projects [\#22](https://github.com/raster-foundry/raster-foundry-api-spec/pull/22)
- Add permission routes to first class auth objects [\#18](https://github.com/raster-foundry/raster-foundry-api-spec/pull/18)
- Add scene datasource endpoint [\#17](https://github.com/raster-foundry/raster-foundry-api-spec/pull/17)
- Cleanup from secondary auth [\#16](https://github.com/raster-foundry/raster-foundry-api-spec/pull/16)
- Add sceneType to Scene [\#11](https://github.com/raster-foundry/raster-foundry-api-spec/pull/11)
- Add MODIS_USGS upload type [\#9](https://github.com/raster-foundry/raster-foundry-api-spec/pull/9)
- Add platforms and organizations Spec [\#8](https://github.com/raster-foundry/raster-foundry-api-spec/pull/8)

* _This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)_
