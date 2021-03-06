# Change Log

## [Unreleased]

## [v2.1.3] - 2017-11-20
### Changed
- README (Contributing)

## [v2.1.2] - 2017-11-20
### Added
- CONTRIBUTING.md

### Changed
- README (table of contents / npm package version / languages supported by default)
- Moved CHANGELOG.md to `docs` folder

## [v2.1.1] - 2017-11-17

### Fixed
- Fixed Typescript declaration file: set `selectedNodes: string[],` option as optional `selectedNodes?: string[],` 

## [v2.1.0] - 2017-11-17

### Added
- Localization for portuguese-brazilian (`ptbr`)
- New option `selectedNodes` to pre-select one or more nodes

### Changed
- Event `searchareacontrol.afterinit` fires 10ms later

## [v2.0.0] - 2017-11-14

### Added
- Localization functionality (English (`en`) and Greek (`el`))

### BREAKING CHANGE
- Name of option `modallHeader` has changed to `modalHeader`

## [v1.6.0] - 2017-11-09

### Added

- Event `searchareacontrol.popup.beforeshow`
- Event `searchareacontrol.popup.beforehide`

## [v1.5.1] - 2017-11-04

### Changed
- README (Added documentation)

## [v1.5.0] - 2017-11-04

### Added
- Regular expression search

### Changed
- `searchareacontrol.selectedNodesChanged` event returns object with 3 properties (`element`, `selectedAll`, `selectedNodes`)

## [v1.4.2] - 2017-10-23

### Fixed
- Typescript declaration file
- Search box selected nodes span

## [v1.4.1] - 2017-10-23

### Fixed
- Typescript declaration file

## [v1.4.0] - 2017-10-22

### Added
- Typescript declaration file
- `searchareacontrol.selectedNodesChanged` event

### Changed
- `getSelectedByAttribute` method's parameter gets **optional**
- README (Added NPM section and new event)

## [v1.3.6] - 2017-10-09

### Fixed
- Corrected type error
 
## [v1.3.5] - 2017-10-09

### Fixed
- IE11 Error in 'strict mode': *Assignment to read-only properties is not allowed in strict mode* for `classList` change (=> .style.cssText) 

## [v1.3.4] - 2017-08-29

### Added
- getPopup() method: Returns the jQuery object instance of the specific popup element
- setDisabledNodes(collection, diselectDisabled, byAttribute): Disables specified nodes
- enableAllNodes(): Enables all nodes
- disableAllNodes(): Disbales all nodes

### Changed
- setSelectedNodes(allSelected, collection, byAttribute): New optional parameter `byAttribute`
- Removed 'group' property from plugin data format

## [v1.3.3] - 2017-08-25

### Fixed
- updateDatasource() method: Updates datasource and rebuilds popup

## [v1.3.2] - 2017-08-03

### Added
- CHANGELOG file
- Custom events

### Changed
- README (Added events section)

## [v1.3.1] - 2017-08-02

### Changed
- Options: popupDimensions object (multiple window width breakpoints)

## [v1.3.0] - 2017-08-01

### Added
- Test page (test.html)

### Fixed
- Mixed data for multiple plugin instances


[Unreleased]: https://github.com/kapantzak/SearchAreaControl/compare/master...develop
[v2.1.3]: https://github.com/kapantzak/SearchAreaControl/compare/v2.1.2...v2.1.3
[v2.1.2]: https://github.com/kapantzak/SearchAreaControl/compare/v2.1.1...v2.1.2
[v2.1.1]: https://github.com/kapantzak/SearchAreaControl/compare/v2.1.0...v2.1.1
[v2.1.0]: https://github.com/kapantzak/SearchAreaControl/compare/v2.0.0...v2.1.0
[v2.0.0]: https://github.com/kapantzak/SearchAreaControl/compare/v1.6.0...v2.0.0
[v1.6.0]: https://github.com/kapantzak/SearchAreaControl/compare/v1.5.1...v1.6.0
[v1.5.1]: https://github.com/kapantzak/SearchAreaControl/compare/v1.5.0...v1.5.1
[v1.5.0]: https://github.com/kapantzak/SearchAreaControl/compare/v1.4.2...v1.5.0
[v1.4.2]: https://github.com/kapantzak/SearchAreaControl/compare/v1.4.1...v1.4.2
[v1.4.1]: https://github.com/kapantzak/SearchAreaControl/compare/v1.4.0...v1.4.1
[v1.4.0]: https://github.com/kapantzak/SearchAreaControl/compare/v1.3.6...v1.4.0
[v1.3.6]: https://github.com/kapantzak/SearchAreaControl/compare/v1.3.5...v1.3.6
[v1.3.5]: https://github.com/kapantzak/SearchAreaControl/compare/v1.3.4...v1.3.5
[v1.3.4]: https://github.com/kapantzak/SearchAreaControl/compare/v1.3.3...v1.3.4
[v1.3.3]: https://github.com/kapantzak/SearchAreaControl/compare/v1.3.2...v1.3.3
[v1.3.2]: https://github.com/kapantzak/SearchAreaControl/compare/v1.3.1...v1.3.2
[v1.3.1]: https://github.com/kapantzak/SearchAreaControl/compare/v1.3.0...v1.3.1
[v1.3.0]: https://github.com/kapantzak/SearchAreaControl/compare/v1.2.2...v1.3.0