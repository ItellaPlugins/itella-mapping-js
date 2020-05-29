# Changelog

## [1.2.2] - 2020-05-29
### Added
- MutationObserver to detect removal of main container (element displaying currently selected point and map open button) so modal is also removed

### Fixed
- Map modal is now attached at the end of document.body (fixes triggering form submit when using ENTER key inside map modal)

### Updated
- Removed unused code
- updated build tools

## [1.2.1] - 2020-05-29
### Fixed
- Leaflet plugins registration now first checks if plugin already registered (fixes activeArea plugin issue for multiple registrations)

## [1.2.0] - 2020-05-21
### Added
- Leaflet.markercluster and Leaflet-active-area plugins integrated into itella-mapping.js (so we can controll when these plgins are added to Leaflet).

## [1.1.0] - 2020-05-21
### Added
- Marker clustering (uses Leaflet.markercluster)
- Sample locations JSON for Finland (locations_FI.json)
- This changelog file
- Required dependencies example to readme.md

## [1.0.0] - Initial release