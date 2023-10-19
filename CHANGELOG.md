# Changelog

This repository adheres to semantic versioning and follows the conventions of [keepachangelog.com](http://keepachangelog.com).
 
## 1.0.0 - 2023-10-19
### Changed
- **BREAKING**
  - Require react-native >= 0.68.7 due to removal of `fallbackResource` parameter in react-native's `[RCTBundleURLProvider sharedSettings]` function
  - Remove `fallbackResource` parameter when getting bundle url using `[RCTBundleURLProvider sharedSettings]` function in `ThreadManager.m`
  - Fixes https://github.com/joltup/react-native-threads/issues/147
- Move podspec to root directory
  - Fixes https://github.com/joltup/react-native-threads/issues/154
