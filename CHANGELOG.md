# Change log

## v0.6.6
- Fixed the issue where the upsert node stopped loading because the variable `pattern` had been declared elsewhere. Thanks to Dave Cahill (https://github.com/davecahill) for the hint.

## v0.6.4
- The 'get data' node can now handle parameters other than 'limit'. Parameters can be passed to the node using `msg.coda.params`.

## v0.6.1
Added input validation to the following nodes:
- Connection settings (excludes the API token and document ID fields)
- Get data
- Upsert

## v0.6.0
**This release contains a change that is not backward-compatible. Please update your settings in the 'Connection settings' node**
- Coda API tokens no longer get exported when nodes/flows are exported for improved security

## v0.5.1
- Updated the documentations

## v0.5.0
**This release contains a change that is not backward-compatible. Please update your settings in the 'Connection settings' node**
- Added the option to choose whether to retrieve rows or columns

## v0.4.1
Release date: 2018-12-09
- Added package-lock.json

## v0.4.0
Release date: 2018-12-08

**This release contains a change that is not backward-compatible. Please update your settings in the 'Connection settings' node**
- Added the option to select between tables, folders and sections. Previously it provided no options
