# Changelog

This repository adheres to semantic versioning and follows the conventions of [keepachangelog.com](http://keepachangelog.com).

## 1.0.3 - 2023-11-07
### Fixed
- Bundle not loading correctly, see https://github.com/joltup/react-native-threads/issues/139#issuecomment-1103094007

## 1.0.2 - 2023-10-30
### Changed
- Commit package-lock.json file

### Fixed
- Wrong path to package.json file in podspec

## 1.0.1 - 2023-10-27
### Fixed
- iOS podspec not included in npm package

## 1.0.0 - 2023-10-19
### Changed
- **BREAKING**
  - Require react-native >= 0.68.7 due to removal of `fallbackResource` parameter in react-native's `[RCTBundleURLProvider sharedSettings]` function
  - Remove `fallbackResource` parameter when getting bundle url using `[RCTBundleURLProvider sharedSettings]` function in `ThreadManager.m`
  - Fixes https://github.com/joltup/react-native-threads/issues/147
- Move podspec to root directory
  - Fixes https://github.com/joltup/react-native-threads/issues/154
