# Change Log
Changelog registry

## 2021-02-03
### Added
- Allow custom metadata type in folder and file creation.

## 2021-02-01
### Added
- method to upload a file with a final file name (usefull when upload resources from a ByteArrayResource that doesn't returns a filename).
- method to list files inside a folder by server folder remote url.

## 2020-12-03
### Added
- methods for folder and file listing of a folder
- support for HTTP protocol for on-premises
- digestKey usage for on-premises
- returns InputStream from downloadFile to support large files for on-premises


## 2020-09-25

### Changed
- Separate implementations for sharepoiont online and on premises
- Added a interface to use both immplementations as one unique interface


## 2020-07-17
### Added
- Tested new methods to retrieve list fields
- Added helper to build request headers

### Changed
- BugFix Solved in getting list items.


## 2020-07-16
### Added
- Added method to create a list
- Added method to update a list description

### Changed
- BugFix Solved issue on getting folder permissions (trying to iterate over JSONArray not possible).


## 2020-07-15
### Changed
- BugFix Solved issue with special characters in list, files and folder names.


## 2020-07-14
### Added
- Remove a permission to all users in a folder (requires unique permissions in folder).
- Added method to retrieve all role assignments of a folder in a sharepoint list.
