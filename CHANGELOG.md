# Change Log

## 0.2.0 Release

* Fixed library resolution in multi-root CQL projects (known issue: all CQL projects included in a multi-root project must use the same version of FHIRHelpers.  Multiple versions of FHIRHelpers in a multi-root CQL project will result in errors and is not currently supported)
* Fixed URI handling issues on Windows
  * These changes fixed numerous bugs on Windows, such as the return type hover, the error highlighting, the execute ELM functionality

## 0.1.7 - Prerelease

* Size reductions in plugin

## 0.1.6 - Prerelease

* Update to cql-language server 1.5.8
  * Multi-root workspace support
  * Performance enhancements

## 0.1.5

* Update to cql-language server 1.5.7

## 0.1.4

* Update to cql-language server 1.5.6

## 0.1.3

* Update to cql-language server 1.5.4
  * fixes for CQL 1.5
  * fixes for duplicate problems
  * fixes for no error highlighting on certain CQL files
  * fixes for null pointer exceptions in output

## 0.1.2

* Add support for cql-options.json file in the cql directory
* Updated dependencies
  * cql-translator 1.5.6
  * cql-evaluator 1.4.1

## 0.1.1

* Fixes for test discovery found in review

## 0.1.0

* Initial preview release
* Supports syntax highlighting, error highlighting, viewing ELM, and local execution
* Feature parity with [Atom CQL plugin](https://github.com/cqframework/atom_cql_support)
