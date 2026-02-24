## 1.0.2
### Fixed
- **Android**: Custom info window appearing offset (shifted bottom-right) from the marker on Android devices. `GoogleMapController.getScreenCoordinate()` returns physical pixels on Android but logical pixels on iOS — the coordinates are now normalized by dividing by `devicePixelRatio` on Android to match Flutter's logical pixel coordinate system.

## 1.0.1

- 🎉 Initial release of `google_map_custom_info_window`
- Added `GoogleMapCustomInfoWindow` widget
- Supports custom titles, close button, and dynamic resizing
- Works with Android, iOS, and Web (with Google Maps JS API)

