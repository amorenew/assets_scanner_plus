## 3.0.0

* Migrate to build: 3.0.0
* Add custom output file name to fix
https://github.com/amorenew/assets_scanner_plus/issues/1
* Handle dublicate names but different extension to fix
https://github.com/amorenew/assets_scanner_plus/issues/2
## 2.0.0

* Migrating to null-safety
* Rename `lib/assets_scanner_plus_builder.dart` to `lib/assets_scanner_plus.dart`

## 1.2.0+1

* Fix dart format

## 1.2.0

* Ensure constant naming conforms the dart variable naming rules

## 1.1.2

* Remove unnecessary `analyzer` package dependencies
* Bump packages versions

## 1.1.1
Add more `ignore_for_file` rules for the generated file.

## 1.1.0+1
Support [package assets](https://flutter.dev/docs/development/ui/assets-and-images#bundling-of-package-assets). 

## 1.0.1
Fix the generated content not respect the directory behavior of assets, that describe on https://flutter.dev/docs/development/ui/assets-and-images#specifying-assets

> Note: Only files located directly in the directory are included. To add files located in subdirectories, create an entry per directory.

## 1.0.0
Refactor the assets_scanner_plus to generate the `r.dart` file, and custom it by adding `assets_scanner_plus_options.yaml` file, see more detail from `README.md`.

## 0.0.2
Allow not generate comment for asset path by setting `const bool isIgnoreComment = true;`

## 0.0.1
Release 0.0.1
